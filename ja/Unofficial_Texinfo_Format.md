# 非公式Texinfoフォーマット

これは<abbr title="Structure and Interpretation of Computer Programs">SICP</abbr>の非公式Texinfo版[^訳注1]の第二版です。

あなたはきっと、これをEmacsのInfoモードのようなInfoハイパーテキストブラウザで読んでいるのでしょう。もしかすると、$\LaTeX$で組版されたものを画面上で、または印刷して読んでいるのかもしれませんね。もっとも、それは間抜けなことだと思いますが。それに、印刷するにはだいぶお金がかかりますよね。

<abbr title="HyperText Markup Language">HTML</abbr>-<abbr title="Graphics Interchange Format">GIF</abbr>版は公式に無料で公開されているのですが、それを初めてUnofficial Texinfo Format(非公式Texinfo版、<abbr title="Unofficial Texinfo Format">UTF</abbr>)の初版としてLytha Aythが個人的に変換したのは、2001年4月の長いEmacs Lovefest Weekendの間のことでした。

<abbr title="Unofficial Texinfo Format">UTF</abbr>は<abbr title="HyperText Markup Language">HTML</abbr>版よりも検索が簡単です。また、あまりよくないコンピュータ(例えば寄付された386マシンのようなもの)を使っている人にとってもアクセスしやすいでしょう。
386マシンは、理論的には、Linux、Emacs、Schemeインタプリタを同時に実行できます。
しかし、多くの386マシンでは、Netscapeとそれに必要なX Window Systemの両方を動かそうとすると、まだ始めたてでお金もない若いハッカーに**スラッシング**(_thrashing_)という概念を早い段階から教えるはめになるのがオチです。それに、<abbr title="Unofficial Texinfo Format">UTF</abbr>版なら圧縮なしで1.44<abbr title="megabyte">MB</abbr>のフロッピーディスクに収まりますので、インターネットや<abbr title="Local Area Network">LAN</abbr>への接続環境のないPCに
インストールするのにも便利です。

Texinfoへの変換は、可能な範囲で直接的な翻字をしました。$\TeX$から<abbr title="HyperText Markup Language">HTML</abbr>への変換のように、これによってある程度内容が損なわれてしまいました。非公式TexInfo形式では、図はいにしえの技術であるアスキーアートによって不格好に復活させられることになりました。
また、多量の上付き文字(‘ˆ’)と下付き文字(‘_’)を変換するうちに、曖昧さによる変換ミスが含まれてしまった可能性も大いにあります。どれが変換ミスかを当てるのは、読者への課題とします。
しかし、少なくとも私たちは、**“より大きい”**という記号を$\texttt{<u>\&gt;</u>}$と符号化して私たちの勇敢な宇宙飛行士たちを危険にさらすようなことはしていません。

もしあなたが$\texttt{sicp.texi}$を変更して間違いを直したりアスキーアートを改善したりした場合、$\texttt{@set utfversion 2.andresraba5.5}$の行を更新し、あなたの差分を反映してください。
例えば、もしあなたがLythaのバージョン$\texttt{1}$から始めていて、あなたの名前がBobなら、改訂版には$\texttt{1.bob1}$, $\texttt{1.bob2}$, $\dots$ , $\texttt{1.bob\textit{n}}$のように名前をつけるのがいいでしょう。
また、$\texttt{utfversiondate}$も更新してください。もしあなたが自分の改訂版をWeb上で配布したいのなら、文字列“sicp.texi”をファイルやWebページのどこかに埋め込んでおけば、Web検索エンジンから見つけやすくなるでしょう。

非公式Texinfo形式は、寛大にもフリーに配布されている<abbr title="HyperText Markup Language">HTML</abbr>版の魂を引き継いでいると信じられています。しかし、いつどこかの法律家の大艦隊が、何でもないような小さなことをめぐって大騒ぎをしないとも限りません。ですから、あなたのフルネームを使ったり、あなたのアカウント名やマシン名を含むかもしれないInfo, <abbr title="device-independent file format">DVI</abbr>, PostScript, <abbr title="Portable Document Format">PDF</abbr>版を配布したりするのは慎重に考えてからにしてください。

_Peath, Lytha Ayth_

**付録:**AbelsonとSussmanによる<abbr title="Structure and Interpretation of Computer Programs">SICP</abbr>のビデオレクチャーもご覧ください。
[<abbr title="Massachusetts Institute of Technology Computer Science and Artificial Intelligence Laboratory">MIT CSAIL</abbr>](http://groups.csail.mit.edu/mac/classes/6.001/abelson-sussman-lectures/), [<abbr title="Massachusetts Institute of Technology OpenCourseWare">MIT OCW</abbr>](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/).

**付録2:**上記は2001年の元の<abbr title="Unofficial Texinfo Format">UTF</abbr>の紹介です。
10年後のいま、<abbr title="Unofficial Texinfo Format">UTF</abbr>は一変しました。数学上の記号と式は適切に組版され、図はベクターグラフィックにより描かれています。元のテキスト形式とアスキーアートの図は今でもTexinfoのソースに残っていますが、表示されるのはInfo形式にコンパイルした場合だけです。
電子書籍リーダーとタブレットの夜明け時代になって、画面上で<abbr title="Portable Document Format">PDF</abbr>を読むことは、もはや馬鹿馬鹿しいことではないとはっきり言えるようになりました。
楽しんでください！

---

[^訳注1]: 英語版にはTexinfo版がありますが、日本語版にはありません。$\LaTeX$ソースとPDFのみです。