In case of ambiguities, the English version prevails.

~~[繁體中文](README-zhT.md) | [简体中文](README-zhS.md)~~ (severely outdated)

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
* Older versions of j83-32 from `gnu-intlfonts` [are actually derived from Watanabe](https://www.rpmfind.net/linux/RPM/opensuse/16.0/noarch/intlfonts-1.2.1-slfo.1.1.2.noarch.html) which is known for plagiarising the proprietary font TypeBank Mincho-M. The newer versions of j83-32 and j83-48 in `gnu-intlfonts` consists of merely an upscaled jiskan16 and an upscaled jiskan24 with no other difference. (The older versions of j83-48 is assumed to be from JIS, so it is kept here.)
* Though the Huiwen Mincho font file states "Public Domain", the longer license summary on Maoken states that the fonts cannot be resold nor reuploaded for commercial purposes. The license of Huiwen fonts is actually equivalent to the OFL; this was proven by the creator of the fonts, and is reflected via CooperZhengKai and Planschrift.
* All et- and taipei- fonts are not in the public domain, contrary to the "Public Domain" statement in the fonts themselves. This includes taipei16, taipei24, and taipei(k,l,m)24, all of which are previously thought to be in the public domain.
  * "Redistributing fonts file of taipei\* and et\* is prohibited. All taipei\* and et\* are protected by copyright law so any commerical use is also prohibited." Source: <https://www.ibiblio.org/pub/packages/ccic/software/fonts/big5/bdf/etenb5.ftpsite>
* The CMEX Big5+ (a.k.a. big5p or cmex24m.bdf) fonts are licensed under MIT, despite the files saying "Public Domain".
* hanja65, from `cjk-fonts`, [derives from HLaTeX-0.92e](https://ctan.org/pkg/cjk-fonts), which [is not under the public domain](https://ctan.org/pkg/hlatex-fonts).
* cns40 (and its 24px variant), from `cjk-fonts` and formerly in `gnu-intlfonts`, is probably licensed under the Open Government Data License.
* The Mona font uses outlines from the Wadalab fonts, which are licensed under the 3-clause BSD license.

## Uncertainties

See `dubious`.

## Other Relevant Notes

* `cjk-fonts` on CTAN claims to be fully public domain, but this claim cannot be verified for all included fonts, and some fonts are blatantly not in the public domain (see ntukai48).
* `gnu-intlfonts` is a collection of libre fonts, but they are not necessarily in the public domain.
