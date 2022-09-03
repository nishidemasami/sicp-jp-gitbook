# Unofficial Texinfo Format

This is the second edition <abbr title="SICP">SICP</abbr> book, from Unofficial Texinfo
Format.

You are probably reading it in an Info hypertext browser, such as the Info
mode of Emacs.  You might alternatively be reading it $TeX$-formatted on your
screen or printer, though that would be silly.  And, if printed, expensive.

The freely-distributed official <abbr title="HTML">HTML</abbr>-and-<abbr title="GIF">GIF</abbr> format was
first converted personally to Unofficial Texinfo Format (<abbr title="UTF">UTF</abbr>)
version 1 by Lytha Ayth during a long Emacs lovefest weekend in April, 2001.

The <abbr title="UTF">UTF</abbr> is easier to search than the <abbr title="HTML">HTML</abbr> format.  It is
also much more accessible to people running on modest computers, such as
donated '386-based PCs.  A 386 can, in theory, run Linux, Emacs, and a Scheme
interpreter simultaneously, but most 386s probably can't also run both Netscape
and the necessary X Window System without prematurely introducing budding young
underfunded hackers to the concept of _thrashing_.  <abbr title="UTF">UTF</abbr> can also fit
uncompressed on a 1.44<abbr title="MB">MB</abbr> floppy diskette, which may come in handy for
installing <abbr title="UTF">UTF</abbr> on PCs that do not have Internet or <abbr title="LAN">LAN</abbr> access.

The Texinfo conversion has been a straight transliteration, to the extent
possible.  Like the $TeX$-to-<abbr title="HTML">HTML</abbr> conversion, this was not without
some introduction of breakage.  In the case of Unofficial Texinfo Format,
figures have suffered an amateurish resurrection of the lost art of
<abbr title="ASCII">ASCII</abbr>.  Also, it's quite possible that some errors of ambiguity
were introduced during the conversion of some of the copious superscripts (‘ˆ’)
and subscripts (‘_’).  Divining **which** has been left as an exercise to
the reader. But at least we don't put our brave astronauts at risk by encoding
the **greater-than-or-equal** symbol as $\texttt{<u>\&gt;</u>}$.

If you modify “sicp.texi” to correct errors or improve the
<abbr title="ASCII">ASCII</abbr> art, then update the $\texttt{@set utfversion 2.andresraba5.5}$
line to reflect your delta.  For example, if you started with Lytha's version
$\texttt{1}$, and your name is Bob, then you could name your successive versions
$\texttt{1.bob1}$, $\texttt{1.bob2}$, … $\texttt{1.bob\textit{n}}$.  Also update
$\texttt{utfversiondate}$.  If you want to distribute your version on the Web, then
embedding the string “sicp.texi” somewhere in the file or Web page will make
it easier for people to find with Web search engines.

It is believed that the Unofficial Texinfo Format is in keeping with the
spirit of the graciously freely-distributed <abbr title="HTML">HTML</abbr> version.  But you
never know when someone's armada of lawyers might need something to do, and get
their shorts all in a knot over some benign little thing, so think twice before
you use your full name or distribute Info, <abbr title="DVI">DVI</abbr>, PostScript, or
<abbr title="PDF">PDF</abbr> formats that might embed your account or machine name.

_Peath, Lytha Ayth_
