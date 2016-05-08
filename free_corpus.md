# Text corpus
This is a list of text corpora available to free of charge

1st row is description, 2nd is URL, and last is license or terms of use (if any)

## Japanese

### Annotated

#### 京都大学テキストコーパス (京大コーパス)
- 毎日新聞の記事に各種言語情報を人手で付与したテキストコーパスです。95年1月1日から17日までの全記事、約2万文、1月から12月までの社説記事、約2万文、計約4万文に対して、形態素・構文情報を付与しています。これらの情報は、形態素解析システムJUMAN、構文解析システムKNPで自動解析を行い、その結果を人手で修正したものです。さらに、このうちの5,000文に対しては、格関係、照応・省略関係、共参照の情報を付与しています。
- http://nlp.ist.i.kyoto-u.ac.jp/index.php?%E4%BA%AC%E9%83%BD%E5%A4%A7%E5%AD%A6%E3%83%86%E3%82%AD%E3%82%B9%E3%83%88%E3%82%B3%E3%83%BC%E3%83%91%E3%82%B9

#### NAISTテキストコーパス
- 京都テキストコーパスで利用されている毎日新聞95年1月1日から17日まで の全記事、約2万文、1月から12月までの社説記事、約2万文、計約4万文に対して，述語と表層格（ガ格，ヲ格，ニ格）の関係，事態性名詞と表層格（ガ格， ヲ格，ニ格）の関係，事態性名詞の名詞クラス，名詞句間の共参照関係，指示連体詞・代名詞の照応関係の情報を付与したコーパスです．
- https://sites.google.com/site/naisttextcorpus/
- 修正 BSD ライセンス

#### 解析済みブログコーパス (KNBC)
- 4テーマ（京都観光、携帯電話、スポーツ、グルメ）、249記事、4,186文の解析済みブログコーパス。形態素、構文、格・省略・照応、評判情報がアノテーションされている。
- http://nlp.ist.i.kyoto-u.ac.jp/kuntt

#### 言語モデル配布ページ
- ウェブデータ、現代日本語書き言葉コーパスから作成した音声認識用と仮名漢字変換用の N-gram を配布しています。
- http://plata.ar.media.kyoto-u.ac.jp/gologo/lm.html

#### 場所参照表現タグ付きコーパス
- 本コーパスは，Twitterからランダムにサンプリングしたテキストに現れる，「特定の場所を著者が想定している」と判断できる表現に対して，実際にどのエンティティを指しているかを人手で判断しエンティティ情報を付与したコーパスです．GeoNLPなどのジオパーズシステム，エンティティリンキングシステム等の開発や評価に利用することを想定して構築されました．
- http://www.cl.ecei.tohoku.ac.jp/~matsuda/LRE_corpus/
- creative commons

#### 近代女性雑誌コーパス
- 明治後期～大正期の女性雑誌3種から40冊を抽出した全文コーパス / 本文テキストに、XMLを用いて文書構造・文字・表記に関する情報をタグ付け / 対象雑誌 ：　『女学雑誌』（女学雑誌社）　1894（明治27）年・1895（明治28）年　31冊『女学世界』（博文館）　1909（明治42）年　6冊『婦人倶楽部』（講談社）　1925（大正14）年　3冊 / 総文字数 ： 約210万字 / 著者数 ： 約480人
- http://pj.ninjal.ac.jp/corpus_center/cmj/woman-mag/
- CC BY-NC-ND 3.0

### Raw text
#### livedoor ニュースコーパス (livedoor news corpus)
- 本コーパスは、NHN Japan株式会社が運営する「livedoor ニュース」のうち、下記のクリエイティブ・コモンズライセンスが適用されるニュース記事を収集し、可能な限りHTMLタグを取り除いて作成したものです。
- http://www.rondhuit.com/download.html
- creative commons

#### 青空文庫
- 青空文庫は、誰にでもアクセスできる自由な電子本を、図書館のようにインターネット上に集めようとする活動です。著作権の消滅した作品と、「自由に読んでもらってかまわない」とされたものを、テキストとＸＨＴＭＬ（一部はＨＴＭＬ）形式に電子化した上で揃えています。
- http://www.aozora.gr.jp

#### プロジェクト杉田玄白
- プロジェクト杉田玄白というのは、いろんな文章を勝手に翻訳して公開しちゃうプロジェクトなのだ。プロジェクトグーテンベルグや、青空文庫の翻訳版だと思って欲しい。
- http://www.genpaku.org
- [丸ごとコピーしたいときも、文章自体を変えないで（変える場合にも変えたところを明示すればオッケー）、もとのURLと版権と、転載自由だってのさえ明記すればなーんも文句はつけないので、これも黙ってやってくれ。](http://cruel.org/linkpolicy.html)

#### 日本語ウェブコーパス 2010
- 本コーパスの HTML アーカイブは，ipadic-2.7.0 の見出し語をシードとして，Yahoo! Web API による検索結果に含まれるウェブページを収集したものです．テキストの抽出においては，文字コードを UTF-8 に統一した後，いくつかの記号をデリミタとして文への分割をおこない，さらに文を構成する文字の種類や数によるフィルタリングを施しています．
- http://s-yata.jp/corpus/nwc2010/

#### TomoriNao
- Charlotteのアニメにおける友利奈緒のセリフをまとめました
- https://github.com/tomorinao/corpus

### N-gram
#### Baidu ブログ・掲示板時間軸コーパス
- Baiduのクロールしたウェブデータから、掲示板の書き込みおよびブログの本文を、書き込まれた正確な時間とともに抽出し時系列に並べたデータを元にして作成したコーパスです。2000年1月～2010年7月の期間に対して、各1ヶ月ごとにスライスし、Nグラム（1グラム～3グラム）の統計を計算しています。
- https://web.archive.org/web/*/http://www.baidu.jp/corpus/
- https://web.archive.org/web/20101130153412/http://www.baidu.jp/corpus/Baidu_Terms_and_condition_Corpus.pdf

#### Baidu 絵文字入りモバイルウェブコーパス
- 一般に公開されているAPIやプライベートなAPI、あるいは以下のBaidu絵文字入りモバイルウェブコーパス（Baiduがウェブから抽出した絵文字を含む日本語データから作成したNグラムデータ）です。
- https://web.archive.org/web/*/http://www.baidu.jp/corpus/
- https://web.archive.org/web/20101130153412/http://www.baidu.jp/corpus/Baidu_Terms_and_condition_Corpus.pdf

### etc
#### 言語処理学会論文誌LaTeXコーパス
- 会誌「自然言語処理」に掲載された論文のLaTeXのソースファイル
- http://www.anlp.jp/resource/journal_latex/

## English

### Annotated

#### The Open American National Corpus
- The Open American National Corpus (OANC) is a massive electronic collection of American English, including texts of all genres and transcripts of spoken data produced from 1990 onward. All data and annotations are fully open and unrestricted for any use.
- http://www.anc.org/

### TYPO CORPUS
- This corpus is a collection of typos in tweets. The corpus consists of pairs of a typo and its original form (such as gogle:google). The typos dealt with this research are classified into four types
- http://luululu.com/tweet/

### Raw

#### The 20 Newsgroups data set
- The 20 newsgroups dataset comprises around 18000 newsgroups posts on 20 topics split in two subsets: one for training (or development) and the other one for testing (or for performance evaluation). The split between the train and test set is based upon a messages posted before and after a specific date.
- http://qwone.com/~jason/20Newsgroups

#### The University of Oxford Text Archive (OTA)
- The University of Oxford Text Archive develops, collects, catalogues and preserves electronic literary and linguistic resources for use in Higher Education, in research, teaching and learning. The OTA also gives advice on the creation and use of these resources, and is involved in the development of standards and infrastructure for electronic language resources.
- https://ota.ox.ac.uk/

## Any Language
- OPUS
- OPUS is a growing collection of translated texts from the web. In the OPUS project we try to convert and align free online data, to add linguistic annotation, and to provide the community with a publicly available parallel corpus. 
- http://opus.lingfil.uu.se/
