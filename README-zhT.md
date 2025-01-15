以下資訊一律以英文版本為準。

# 公開領域字體

此儲存庫主要包含CJK（中日韓）字體以及（接近）泛Unicode字體。

我並不擁有這些字體和編碼，但是它們全部都在公開領域中，或是與公開領域相等。

倘如此儲存庫中涉及任何非公開領域的字體或編碼，請建立議題（Issue）。

## 與公開領域相等的授權

此列表並不詳盡。

* [CC0](https://creativecommons.org/publicdomain/zero/1.0/)
* [0BSD](https://opensource.org/license/0bsd)
* [MIT-0](https://opensource.org/license/mit-0)
* [WTFPL](http://www.wtfpl.net/txt/copying/)
* [Unlicense](https://unlicense.org/)
* [mplus Font License](https://spdx.org/licenses/mplus.html)
  * 條件與其他與公開領域相等的授權（例0BSD）幾乎相等，所以此授權應與公開領域相等

## 非公開領域

* ntukai48 是 `cjk-fonts` 的字體，但寫明 "These fonts must not be used for any commercial activities."
* 從 `gnu-intlfonts` 較舊版本的 j83-32 和 j83-48 [其實源於渡邊字體](https://www.rpmfind.net/linux/RPM/opensuse/16.0/noarch/intlfonts-1.2.1-slfo.1.1.2.noarch.html)，抄襲 TypeBank Mincho-M；而較新的版本只是提高像素的 jiskan16 和 jiskan24，沒有其他改變。
* Mona 的像素字確實是公開領域，但 [Mona-outline 基於 Kochi-substitute](https://en.wikipedia.org/wiki/Mona_(font))，[而它並非開領域](https://ja.wikipedia.org/wiki/%E6%9D%B1%E9%A2%A8%E3%83%95%E3%82%A9%E3%83%B3%E3%83%88)。
* 匯文字體雖提及 "Public Domain"，但貓啃網上較長的授權聲明不允許第三方收費提供或分發。

## 未知狀態

* 從 `cjk-fonts` 和較前從 `gnu-intlfonts` 的 cns40 的授權不明顯。
* 從 `cjk-fonts` 的 hanja65 [可能從某版本的 hLaTeX 而來](https://ctan.org/pkg/cjk-fonts)。`cjk-fonts` 沒有明確標明此 hLaTeX 版本，但是我得知的版本[並非公開領域](https://ctan.org/pkg/hlatex-fonts)。
* 從 `cjk-fonts` 的 jfs56 來源不明，有可能是 CCDOS。[Debian 認為它處於公開領域，](https://sources.debian.org/src/hbf-jfs56/1.0-3.2/debian/copyright/)但它的語法令我極度懷疑。

## 其他

* `cjk-fonts` 聲稱完全公開領域，但當中並非所有字體的授權都能核對，有些字體如 ntukai48 更明顯地並非公開領域。
* `gnu-intlfonts` 雖是自由的字體（≈"開源"），但當中的字體並非一定處於公開領域。
