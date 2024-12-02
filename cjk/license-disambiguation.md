# License Disambiguation

*Disclaimer: GitHub might have misinterpreted this file as a license. This is not a license and merely disambiguates the legal status of some fonts and reasons for not including them.*

## What is NOT Public Domain

* ntukai48, from `cjk-fonts`, mentions "These fonts must not be used for any commercial activities."
* Older versions of j83-32 and j83-48 from `gnu-intlfonts` [are actually derived from Watanabe](https://www.rpmfind.net/linux/RPM/opensuse/16.0/noarch/intlfonts-1.2.1-slfo.1.1.2.noarch.html) which is known for plagiarising the proprietary font TypeBank Mincho-M. The newer version in `gnu-intlfonts` consists of merely an upscaled jiskan16 and an upscaled jiskan24 with no other difference.
* Though the Mona bitmap glyphs are indeed in the public domain, [Mona-outline is based on Kochi-substitute](https://en.wikipedia.org/wiki/Mona_(font)), [which is not in the public domain](https://ja.wikipedia.org/wiki/%E6%9D%B1%E9%A2%A8%E3%83%95%E3%82%A9%E3%83%B3%E3%83%88).

## Uncertainties

* cns40, from `cjk-fonts` and formerly in `gnu-intlfonts`, uses unclear licensing.
* hanja65, from `cjk-fonts`, [possibly derives from a version of hLaTeX](https://ctan.org/pkg/cjk-fonts) which [may not be under the public domain](https://ctan.org/pkg/hlatex-fonts).
* jfs56, from `cjk-fonts`, comes from an unknown source (possibly CCDOS). [Debian assumes that it is under the public domain](https://sources.debian.org/src/hbf-jfs56/1.0-3.2/debian/copyright/) but I doubt it.

## Other Relevant Notes

* `cjk-fonts` on CTAN claims to be fully public domain, but this claim cannot be verified for all included fonts, and some fonts are blatantly not in the public domain (see ntukai48).
* `gnu-intlfonts` is a collection of libre fonts, but they are not necessarily in the public domain.
