以下资讯一律以英文版本为准。

# 公开领域字体

此储存库主要包含CJK（中日韩）字体以及（接近）泛Unicode字体。

我并不拥有这些字体和编码，但是它们全部都在公开领域中，或是与公开领域相等。

倘如此储存库中涉及任何非公开领域的字体或编码，请建立议题（Issue）。

## 非公开领域

* ntukai48 是 `cjk-fonts` 的字体，但写明 "These fonts must not be used for any commercial activities."
* 从 `gnu-intlfonts` 较旧版本的 j83-32 和 j83-48 [其实源于渡边字体](https://www.rpmfind.net/linux/RPM/opensuse/16.0/noarch/intlfonts-1.2. 1-slfo.1.1.2.noarch.html)，抄袭TypeBank Mincho-M；而较新的版本只是提高像素的jiskan16 和jiskan24，没有其他改变。
* Mona 的像素字确实是公开领域，但[Mona-outline 基于Kochi-substitute](https://en.wikipedia.org/wiki/Mona_(font))，[而它并非开领域](https:/ /ja.wikipedia.org/wiki/%E6%9D%B1%E9%A2%A8%E3%83%95%E3%82%A9%E3%83%B3%E3%83%88)。
* 汇文字体虽提及 "Public Domain"，但猫啃网上较长的授权声明不允许第三方收费提供或分发。

## 未知状态

* 从 `cjk-fonts` 和较前从 `gnu-intlfonts` 的 cns40 的授权不明显。
* 从 `cjk-fonts` 的 hanja65 [可能从某版本的 hLaTeX 而来](https://ctan.org/pkg/cjk-fonts)。`cjk-fonts` 没有明确标明此 hLaTeX 版本，但是我得知的版本[并非公开领域](https://ctan.org/pkg/hlatex-fonts)。
* 从 `cjk-fonts` 的 jfs56 来源不明，有可能是 CCDOS。 [Debian 认为它处于公开领域，](https://sources.debian.org/src/hbf-jfs56/1.0-3.2/debian/copyright/)但它的语法令我极度怀疑。

## 其他

* `cjk-fonts` 声称完全公开领域，但当中并非所有字体的授权都能核对，有些字体如 ntukai48 更明显地并非公开领域。
* `gnu-intlfonts` 虽是自由的字体（≈"开源"），但当中的字体并非一定处于公开领域。
