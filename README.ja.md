The Extensible Web Manifesto
============================

私たち -[このマニフェストへの署名者](https://extensiblewebmanifesto.org/#signatories)- は、 Web 標準化団体が新しい機能の追加やその優先順位を決めるために取ってきた、旧来の方法を変えるべきだと主張します。これは、これから先の長い期間に渡って、 Web が健全であるために必要なことだと考えているからです。

第一の目標は、Web 標準仕様のエディタと Web 開発者の間で、しっかりとフィードバックのループがまわることです。
標準化が発展していくモデルとして、手順を重視しトップダウンで決定するモデルよりも、多くの有能な開発者によって駆動するモデルを選びます。

ブラウザベンダは、基盤となるプラットフォームが持つ可能性を、低レベルの機能としてできる限り提供すべきです。
新しい高レベル API を JavaScript による実装をもとに議論できるように、土台を提供すべきです(すでに Mozilla の [X-Tags](http://www.x-tags.org/) や Google の [Polymer](http://www.polymer-project.org/) で行われています)。
これにより、開発者は標準化に参加可能になり、ブラウザの外で議論が繰り返されることで、粗悪な API が定義されるのを防ぎます。

特に、 Extensible Web プラットフォームに対して、以下の方針を提唱します。
* 標準化プロセスは、 Web プラットフォームに対するセキュアで効果的な ***新しい低レベルな機能*** の策定に注力すべきです。
* Web プラットフォームは、 HTML や CSS などの ***既存の特徴を説明*** する低レベルな機能を提供することで、開発者がそれを理解し再現することが可能となるようにすべきです。
* Web プラットフォームは、開発者が新しい高レベル API の開発・表現・テストを JavaScript で行い、それが標準化される前にくりかえし行えるようにすべきです。これは、 ***価値のあるサイクル*** を仕様策定者と開発者の間にもたらします。
* 標準化プロセスは、これらの方針に従って ***優先順位づけ*** をすべきであり、そうなっていないものは、優先度を見直すべきです。

------

***新しい低レベルな機能*** の仕様化にフォーカスし、その観点から新しい機能を実装することで、

* 新しいセキュリティの問題を抑制することができます。
* ブラウザエンジンが、これから追加する API に影響するような、コア部分の最適化に注力できます。これにより、小さい実装コストで、より良いパフォーマンスを得ることに繋がります。
* ブラウザベンダとライブラリ作者が、開発者のニーズにあった高レベル API としてのライブラリの開発を行えるようになります。

***低レベルな機能の視点から*** 既存の機能とこれから追加される新しい特徴を説明することは
* 実装の複雑さの低減や、バグの減少に貢献します。
* より多くの新機能のポリフィルを可能にします。
* 新しい機能についての学習コストを減らします。学習に必要なコンテンツも、すでにプラットフォームにあるコンセプトをもとに作り直すことができます。

新しい機能の理解を簡単にし、それらをポリフィルすることは ***価値のあるサイクル*** をまわします。
* 開発者は新しい API をより早く試し、仕様が固まる前にプラットフォームに対してフィードバックを送ることができます。
* API を利用する開発者や、ライブラリを提供する作者によって、 API のミスはよりすばやく洗い出され、適切で重要なフィードバックをブラウザベンダやプラットフォームのデザイナに提供することができます。
* ライブラリの作者は、新しい API を用いて知見をため、プラットフォームが進むべき道を示すことができます。

以下の方針に基づいて ***優先順位づけ*** することで、
* (特に短期間の)標準化プロセスを解放し、セキュリティやパフォーマンスへの懸念や、新しいハードウェアなどプラットフォームレベルでしか追加しえない機能の標準化に注力できます。
* Web 開発者とブラウザ由来のライブラリが、コストのかかる調査を主導できます。
* すでに実世界で、実装され意味を成している新しい API があることで、長期に渡る標準化プロセスをシンプルかつ効率化します。


もっと開発者がコードを書いて欲しいと考えています。それは、新しい形式を取り入れる上での標準化のボトルネックを取り除き、ライブラリとフレームワークの作者に、開発のために必要なツールを提供します。

オープンな Web がそれを取りまく競合と競うためには、 Web 開発者の良いアイデアを、Web のインフラの一部とするためのはっきりとした手段が必要です。

このマニフェストに賛同する人々

* Brendan Eich <br>
CTO and SVP Engineering, Mozilla; Creator of JavaScript

* Yehuda Katz <br>
Member, TC39, W3C TAG; Core Team, Ember.js, Rails

* Alex Russell <br>
TC39, W3C TAG; Google Chrome Team

* Brian Kardell <br>
Chair, Extensible Web Community Group, W3C

* François REMY <br>
Co-founder, Extensible Web Community Group, W3C

* Clint Hill <br>
Co-founder, Extensible Web Community Group, W3C

* Marcos Caceres <br> 
Co-founder, Extensible Web Community Group, W3C

* Tom Dale <br>
Core Team, Ember.js

* Anne van Kesteren <br>
Editor of standards, Architecture Astronaut at Mozilla

* Sam Tobin-Hochstadt <br>
Member, TC39

* Domenic Denicola <br>
Co-Editor, Promises/A+

* Chris Eppstein <br>
Maintainer, Sass

* Dave Herman <br>
Mozilla Research and TC39

* Alan Stearns <br>
Member, CSSWG

* Rick Waldron <br>
Member, TC39

* Paul Irish <br>
Google

* Ted Han <br>
Lead Developer, DocumentCloud

* Tab Atkins <br>
Member, CSS WG; Google

-----

**関連エントリ**
* [Extend the Web Forward](http://yehudakatz.com/2013/05/21/extend-the-web-forward/), by Yehuda Katz, このアイデアの詳細を解説したエントリ
* [An Extensible Approach to Browser Security Policy](http://yehudakatz.com/2013/05/24/an-extensible-approach-to-browser-security-policy/), by Yehuda Katz, これらの方法を実践したアプリケーションとして、ブラウザの Content Security Policy の API デザインについての問題についての解説。
* [Dropping the F-Bomb on Web Standards](https://briankardell.wordpress.com/2013/05/17/dropping-the-f-bomb/), by Brian Kardell, 開発者のコミュニティから出たアイデアや言語を、相互接続可能な標準にどう取り込むかについての実践的な議論。
* [Bedrock](http://infrequently.org/2012/04/bedrock/), by Alex Russell, 2012年に、拡張可能な("レイヤリングされた")デザインにもとづくプラットフォームに関する、知見と哲学の詳細な調査。
