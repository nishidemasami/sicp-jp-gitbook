# 第二版~序文

> ソフトウェアが、ほかの何にも似ていないということはあるでしょうか。それは捨てられるためのもので、常にシャボン玉のように見ることがすべてだと。
> 
> ---Alan J. Perlis

この本で扱われている題材は、1980年から<abbr title="Massachusetts Institute of Technology">MIT</abbr>の入門レベルの計算機科学科目の基礎となってきました。初版が発売されたとき、すでにこの教材を使った授業を4年間行っていました。この第二版が出てくるまでには、それからさらに12年が過ぎています。私たちの成果が広く受け入れられ、ほかのテキストにも取り込まれていることについて、私たちはうれしく思っています。私たちは、学生たちがこの本に出てくる考え方やプログラムを身につけ、それらを新しいコンピュータシステムやコンピュータ言語の核として組み込むのを見てきました。古代のタルムードに出てくる言葉遊びを文字通り実現し、私たちの学生は建築者になったのです。このような有能な学生、功績ある建築者を得ることができたのは幸運なことでした。

この版の準備にあたって、何百にものぼるわかりやすい説明を取り込みました。それらは、私たち自身の教育経験や、<abbr title="Massachusetts Institute of Technology">MIT</abbr>やほかの場所の同僚たちのコメントから得られたものです。この本に出てくる主なプログラミングシステムのほとんどを再設計しました。それには一般計算システム、インタプリタ、レジスタマシンシミュレータ、コンパイラが含まれます。さらに、プログラムの例をすべて書き換え、<abbr title="Institute of Electrical and Electronics Engineers">IEEE</abbr> Scheme標準([IEEE 1990](References.md#IEEE))に適合したScheme実装であればどんなものの上でもコードを実行できるようにしました。

この版では、いくつかの新しいテーマに重点を置いています。これらの中で最も重要なものは、計算モデルの中で時間を扱うさまざまなアプローチの中心的な役割を果たしているものです。それらのアプローチには、状態つきのオブジェクト、並行プログラミング、関数型プログラミング、遅延評価、非決定性プログラミングがあります。並行性と非決定性については新たに節を設け、本全体を通してこのテーマを統合させるよう力を尽くしました。

この本の初版は、<abbr title="Massachusetts Institute of Technology">MIT</abbr>の半期の科目のシラバスをなぞったものでした。第二版では、多くの新しい題材を含めたため、半期ですべてをカバーするのは無理でしょう。ですので、講師は教えるべき内容を選ぶ必要があります。私たち自身が講義をする際には、時々論理プログラミング([4.4節](Logic_Programming.md))を飛ばします。学生にはレジスタマシンのシミュレータを使わせますが、その実装([5.2節](A_Register_Machine_Simulator.md))はやりません。そして、コンパイラ([5.5節](Compilation.md))はざっと概要を見るだけです。それでもなお、これは中身の濃い授業です。講師によっては、最初の3章か4章だけをやって、残りの題材は次の科目に譲りたいという人もいるでしょう。

World-Wide-Webサイト [http://mitpress.mit.edu/sicp](http://mitpress.mit.edu/sicp) は、この本の読者に対するサポートを提供しています。それには、この本に出てくるプログラム、プログラミング練習問題のサンプル、補助教材、ダウンロード可能なLispのScheme方言の実装が含まれます。