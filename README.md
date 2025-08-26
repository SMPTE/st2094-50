# SMPTE _ST 2094-50_ - _Dynamic Metadata for Color Volume Transform - Application #5 (Broadcast)_

_This repository is *public*._

Please consult [CONTRIBUTING.md](./CONTRIBUTING.md), [CONFIDENTIALITY.md](./CONFIDENTIALITY.md), [LICENSE.md](./LICENSE.md) and [PATENTS.md](./PATENTS.md) for important notices.

## General
This repository tracks ST 2094-50 - Dynamic Metadata for Color Volume Transform - Application #5 (Broadcast)

_This repository is *public*._

Please consult [CONTRIBUTING.md](./CONTRIBUTING.md), [CONFIDENTIALITY.md](./CONFIDENTIALITY.md), [LICENSE.md](./LICENSE.md) and
[PATENTS.md](./PATENTS.md) for important notices.

Your feedback is welcome at https://github.com/SMPTE/st2059-2/issues.

## Public Committee Draft (PCD) Notice

The following element is made available for a public review period ending no earlier than October 31, 2025, and no later than August 8, 2026:

[SMPTE PCD ST 2094-50](./32NF-PCD-ST-2094-50.pdf)

## Details

Computing and compositing systems must often render multiple sources of content—such as text, images, and video—that can include both standard dynamic range (SDR) and high dynamic range (HDR), on the same display at the same time. In ST 2094-50, we describe a system in which modern operating systems and image compositors display content sources together in a common relative linear color space. This space is anchored around an HDR Reference White level, which is explicitly defined and identified within embedded metadata.<br><br>
An HDR Headroom Range begins above the HDR Reference White. By defining the essential image ranges and using parameterized tone mapping curves in ST 2094-50, we provide several key optimizations:
<ul>
<li>Excellent visual matching between different image formats that require compositing</li>
<li>Adaptive tone mapping, where focal content does not become noticeably darker even when the content includes a greater luminance range than the target display.</li>
<li>Provides subjective metadata points along the tone curve defined by the content creator, preserving creative intent.</li>
</ul>
The functionality of these methods is based on several years of real-world broadcast production, where predefined (static) conversion methods use similar concepts, such as a reference white anchor and compressed HDR highlights. ST 2094-50 advances these ideas by defining a mathematically adaptive system.<br><br>
The basic principles of the static method are described in ITU-R BT.2408-8, Sections 7 and Annex 10. Monitoring practices described in ITU-R BT.2166 similarly anchor side-by-side HDR and SDR monitors around common reference white levels to avoid eye adaptation issues. This practice aligns closely with the compositing approach in ST 2094-50, which also centers on a common “reference white” luminance level.<br><br>
A Public Committee Draft (Public CD) of SMPTE ST 2094-50 is available for review on GitHub: https://github.com/SMPTE/st2094-50. Implementers are encouraged to review the system and provide feedback as soon as possible but no later than September 23rd via GitHub to help improve the document and enhance interoperability across implementations.

## Reporting issues

Please report issues at <https://github.com/SMPTE/st2094-50/issues> or at 10E Chairs <10e-chair@smpte.org>.

## Contributing

The draft version(s) of this document is accessible to SMPTE Standards Community members at <https://github.com/SMPTE/st2094-50-private>.
