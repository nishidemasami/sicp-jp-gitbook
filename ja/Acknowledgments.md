# 謝辞

この本とこのカリキュラムの開発を手助けしてくださった多くの方々に感謝いたします。

私たちの科目は、明らかに“6.231”の知的な系譜を継ぐものです。それは、1960年代後半に<abbr title="MIT">MIT</abbr>でJack WozencraftとArthur Evans, Jr.が担当していた、プログラミング言語学とλ計算についてのすばらしい科目でした。

Robert Fanoが<abbr title="MIT">MIT</abbr>の電気工学と計算機科学の入門カリキュラムを再編成し、工学設計の原理に重点を置くようにしてくれたことに非常に感謝しています。彼はこの取り組みを始めるよう私たちを導き、最初の科目ノートをまとめてくれました。この本は、それをもとに発展してきたものです。

私たちが教えようとしているプログラミングのスタイルと美学は、その多くがGuy Lewis Steele Jr.と連携して開発したものです。彼は、Gerald Jay SussmanとともにScheme言語の初期の開発に携わりました。さらに、David Turner, Peter Henderson,Dan Friedman, David Wise, Will Clingerは、この本に登場する関数プログラミングコミュニティのテクニックを数多く教えてくれました。

Joel Mosesは、大きなシステムを構築する方法を教えてくれました。彼は、記号計算に使われるMacsymaシステムでの開発経験を通して、制御の複雑性を回避して、モデル化しようとしている世界の現実の構造を反映するようデータを体系化することに集中することが重要だということを学んでいました。

Marvin MinskyとSeymour Papertは、プログラミングと、知的生活の中でそれをどのように位置づけるかについて、私たちの姿勢の多くを形作ってくれました。コンピュータがなければ正確に扱うには複雑すぎるような考えを探究するにあたって、コンピュータが表現手段を与えてくれるということを理解できるようになったのは彼らのおかげです。彼らは、学生のプログラムを書き、変更する能力が、自然活動を探究するための強力な方法になると強調しています。

私たちはまた、プログラミングはとても楽しいものであり、プログラミングの楽しみを支えるよう注意しなければいけないというAlan Perlisの考え方に強く同意します。この楽しみの一部分は、偉大な職人たちの働いているところからも得ることができます。Bill GosperやRichard Greenblattのもとで見習いプログラマとして働けたことは幸運なことでした。

私たちのカリキュラムの開発に貢献してくださったすべての方々について名前を挙げるのは困難です。過去15年間私たちと共に働き、私たちの科目に多くの時間を費やしていただいたすべての講師、口頭の指導者、チューターたち、中でもBill Siebert,Albert Meyer, Joe Stoy, Randy Davis, Louis Braida, Eric Grimson, Rod Brooks, Lynn Stein,Peter Szolovitsに感謝します。現在はウェルズリーにいるFranklyn Turbakに、教育上の際立った貢献について特に感謝します。彼の学部生向けの授業は、私たち皆が目指す基準を打ち立てました。Jerry SaltzerとJim Millerには、私たちが並行性のミステリーに取り組むのを手助けしてくださったことを感謝します。そしてPeter SzolovitsとDavid McAllesterには、[第4章](Metalinguistic_Abstraction.md)における非決定性評価の説明に対する貢献に感謝します。

多くの方々が、他大学でこの資料を紹介するのに大きな努力を費やしてくださいました。中でも私たちが緊密に連携していたのは、イスラエル工科大学のJacob Katzenelson、カリフォルニア大学アーバイン校のHardy Mayer、オックスフォード大学のJoe Stoy、パデュー大学のElisha Sacks、ノルウェー技術科学大学のJan Komorowskiです。私たちは、他大学にこの科目を適合させることで主要な教育の賞を受けた同僚たちを非常に誇りに思います。この中には、イェール大学のKenneth Yip、カリフォルニア大学バークレー校のBrian Harvey、コーネル大学のDan Huttenlocherが含まれます。

Al Moyéは、ヒューレット・パッカードの技術者にこの教材を教え、その講義をビデオテープにすることを手配してくれました。これらのビデオを使った生涯教育のコースを計画し、世界中の大学や企業で教えた有能な講師たち、特にJim Miller, Bill Siebert, Mike Eisenbergに感謝します。

第一版の翻訳には、ほかの国の多くの教育者が多大な労力をつぎ込んでくれました。フランス語版はMichel Briand, Pierre Chamard, André Pic、ドイツ語版はSusanne Daniels-Herold、日本語版は元吉文男氏によって製作されています。中国語版は誰が製作したのかわかりませんが、“無許可”翻訳の題材として選ばれたことを光栄に思います。

私たちが教育目的で使用するSchemeシステムの開発に技術的な貢献をしたすべての方々の名前を挙げることは困難です。Guy Steeleのほかに、主なウィザードにはChris Hanson, Joe Bowbeer, Jim Miller, Guillermo Rozas, Stephen Adamsがいます。ほかに多大な時間を費やしてくれた方々は、Richard Stallman, Alan Bawden,Kent Pitman, Jon Taft, Neil Mayle, John Lamping, Gwyn Osnos, Tracy Larrabee,George Carrette, Soma Chaudhuri, Bill Chiarchiaro, Steven Kirsch, Leigh Klotz,Wayne Noss, Todd Cass, Patrick O'Donnell, Kevin Theobald, Daniel Weise,Kenneth Sinclair, Anthony Courtemanche, Henry M. Wu, Andrew Berlin, Ruth Shyu です。

<abbr title="MIT">MIT</abbr>の実装を越えて、私たちは<abbr title="IEEE">IEEE</abbr>のScheme標準仕様に取り組んでくれた多くの人々に感謝したいと思います。その中にはR⁴RSを編集したWilliam ClingerとJonathan Rees、<abbr title="IEEE">IEEE</abbr>標準を準備したChris Haynes, David Bartley,Chris Hanson, Jim Millerが含まれます。

Dan Friedmanは、長い間Schemeコミュニティのリーダーでした。コミュニティの広範な仕事は言語設計の問題を越えて、Schemer's Inc.によるEdSchemeをもとにした高校生向けカリキュラムや、Mike EisenbergやBrian HarveyとMatthew Wrightによるすばらしい本のような、意義深い教育上のイノベーションまで含みます。

私たちは、このコースをちゃんとした本にすることを助けてくれた方々、特に<abbr title="MIT">MIT</abbr>出版のTerry Ehling, Larry Cohen, Paul Bethgeに感謝します。Ella Mazelはすばらしい表紙絵を見つけてくれました。第二版については、特にこの本のデザインを助けてくれたBernardとEllaのMazel夫妻、非凡な$TeX$ウィザードであるDavid Jonesに感謝します。私たちはまた、新しいドラフトに対して洞察力のあるコメントをしてくださった読者の方々、Jacob Katzenelson, Hardy Mayer, Jim Millerに感謝します。そして特にBrian Harveyには、Julieが彼の本_Simply Scheme_にしたのと同じような貢献を返してくれたことを感謝します。

最後に、この作品を何年にもわたって支持してくれた団体に感謝します。その中には、Ira GoldsteinとJoel Birnbaumが実現してくれたヒューレット・パッカードからの支持と、Bob Kahnが実現してくれた<abbr title="DARPA">DARPA</abbr>からの支持を含みます。