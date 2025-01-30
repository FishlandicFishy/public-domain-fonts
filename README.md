In case of ambiguities, the English version prevails.

[繁體中文](README-zhT.md) | [简体中文](README-zhS.md)

# Public Domain Fonts

This repository mainly focuses on public domain CJK fonts and (nearly) pan-Unicode fonts.

I own none of these fonts and scripts, however they are all confirmed to be in the public domain (or public domain-equivalent).

If something here is not in the public domain (or not public domain-equivalent), please create an issue.

## Public Domain-Equivalent Licenses

This list is not exhaustive.

* [CC0](https://creativecommons.org/publicdomain/zero/1.0/)
* [0BSD](https://opensource.org/license/0bsd)
* [MIT-0](https://opensource.org/license/mit-0)
* [WTFPL](http://www.wtfpl.net/txt/copying/)
* [Unlicense](https://unlicense.org/)
* [mplus Font License](https://spdx.org/licenses/mplus.html)
  * Terms are nearly identical to other public domain-equivalent licenses like 0BSD, so I'd assume it's also public domain-equivalent

## What is NOT Public Domain

* ntukai48, from `cjk-fonts`, mentions "These fonts must not be used for any commercial activities."
* Older versions of j83-32 and j83-48 (a.k.a. kanji48) from `gnu-intlfonts` [are actually derived from Watanabe](https://www.rpmfind.net/linux/RPM/opensuse/16.0/noarch/intlfonts-1.2.1-slfo.1.1.2.noarch.html) which is known for plagiarising the proprietary font TypeBank Mincho-M. The newer version in `gnu-intlfonts` consists of merely an upscaled jiskan16 and an upscaled jiskan24 with no other difference.
* Though the Mona bitmap glyphs are indeed in the public domain, [Mona-outline is based on Kochi-substitute](https://en.wikipedia.org/wiki/Mona_(font)), [which is not in the public domain](https://ja.wikipedia.org/wiki/%E6%9D%B1%E9%A2%A8%E3%83%95%E3%82%A9%E3%83%B3%E3%83%88).
* Though the Huiwen font files state "Public Domain", the longer license summary on Maoken states that the fonts cannot be resold nor reuploaded for commercial purposes.

## Uncertainties

* cns40, from `cjk-fonts` and formerly in `gnu-intlfonts`, uses unclear licensing.
* hanja65, from `cjk-fonts`, [possibly derives from a version of hLaTeX](https://ctan.org/pkg/cjk-fonts). It is unclear which version of hLaTeX `cjk-fonts` is talking about but the one I am aware of [is not under the public domain](https://ctan.org/pkg/hlatex-fonts).
* jfs56, from `cjk-fonts`, comes from an unknown source (possibly CCDOS). [Debian assumes that it is under the public domain](https://sources.debian.org/src/hbf-jfs56/1.0-3.2/debian/copyright/) but I doubt it.

## Other Relevant Notes

* `cjk-fonts` on CTAN claims to be fully public domain, but this claim cannot be verified for all included fonts, and some fonts are blatantly not in the public domain (see ntukai48).
* `gnu-intlfonts` is a collection of libre fonts, but they are not necessarily in the public domain.
