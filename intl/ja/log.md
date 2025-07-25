# 100 Days Of Code - 学習ログ

### 1日目: 2025年4月27日

**今日の進捗**
- 「現役シリコンバレーエンジニアが教えるPython 3 入門 + 応用 +アメリカのシリコンバレー流コードスタイル」のUnittestとLoggingについて勉強した

**学んだこと** 
- Unittestはpytestを使った方がコードを簡潔に書けて便利なことや、Eroorのレベルとlogの関係、loggerを使って他のモジュールに引き継ぐなど基本的なことを学べた。

**リンク** 
[現役シリコンバレーエンジニアが教えるPython 3 入門 + 応用 +アメリカのシリコンバレー流コードスタイル](https://www.udemy.com/course/python-beginner/)

### 2日目: 2025年4月28日

**今日の進捗**
- 昨日勉強した内容をもとに自分でコード書いて復習し理解を深めた。具体的には、簡単な決済機能を実装したクラスを用意し、unittestとpytestでテストコードを書いた。
- また、loggingとloggerを使ってファイルにログ出力することができた。

**学んだこと** 
- Udemyで動画見てるときはわかった気になってただけだということが自覚できた。
- ChatGPTに聞きながら実際に自分でコードを書いてみると、どうやって使うのかをより深く理解することができた。

**リンク** 
[現役シリコンバレーエンジニアが教えるPython 3 入門 + 応用 +アメリカのシリコンバレー流コードスタイル](https://www.udemy.com/course/python-beginner/)


### Day 3: 2025年4月29日

**今日の進捗**  
- 今日はグループ支払い- 割り勘アプリの土台になるドメインモデルを作った。  
- `User`、`Payment`、`Asset`、`Debt`とかのデータモデルを定義して、リストを管理するコレクションクラスを実装。  
- さらに、Pydanticで型をしっかり守りながら、ユーザー間の貸し借りを整理するロジックも実装した。

**学んだこと**  
- コード読んでてわからないところがあればChatGPTに質問して一つ一つ理解した。
- これでAPIやフロントエンドと繋げる準備が整った。

**リンク**  
[walicaaa-backend GitHubコミット](https://github.com/takuto-san/walicaaa-backend/commit/89feb00b888489350b104c6af4e7a2ecbd903a4d)


### Day 4: 2025年4月30日

**今日の進捗**  
- 支払い- 精算に関するスキーマを編集し、残高計算と精算ロジックを追加した。
- 全員の支払い履歴から、送金すべき金額と相手を自動算出できるようにした。

**学んだこと**  
- pydanticがわからなくてデータの受け渡しとかに必ず型がついて回ってわかりかねるところが多かった。

**リンク**  
[walicaaa-backend GitHubコミット](https://github.com/takuto-san/walicaaa-backend/commits/main/?since=2025-05-01&until=2025-05-01)


### Day 5: 2025年5月1日

**今日の進捗**  
- 松尾研究所「深層学習 Deep Learning基礎講座 2025」の第3回課題をやった。
- MLPについて学習し、画像認識をするモデルを作成した。

**学んだこと**  
- 課題とは別に自分でAIモデルをPythonスクリプトで実装したら、一層理解が深まった。
- kaggleで公開されているサッカー選手の顔画像データセットを使用して、メッシやロナウドなど8人の選手の顔画像を学習させた。


### Day 6: 2025年5月2日

**今日の進捗**  
- ネットワークをハンズオンで勉強することを目的にcisco packet trackerを始めた。今日は初日なのでチュートリアルに取り組んだ。

**学んだこと**  
- OSI参照モデルなどを使って理論を説明されるより、実際にネットワークを画面上で構成してみた方が飽きないし楽に勉強できる。


### Day 7: 2025年5月3日

**今日の進捗**  
- LeetCodeの「Top Interview 150」を2問解いた
- やることが増えてきたので計画を立ててタスクを整理した

**学んだこと**  
- #100daysofcodeをきっかけに、CSの基礎を固めることを目標に日々学習を継続したい
- まずは、「今使える時間がどれくらいあるか」をベースにタスクを一つ一つ進めていきたい


### Day 8: 2025年5月4日

**今日の進捗**  
- LeetCodeの「Top Interview 150」を2問解いた
- 「ゼロからのOS自作入門」の第1回講義を受けた
- XQuartzインストール → DevContainer（Docker）環境立ち上げ → FATイメージ（disk.img）作成 → BOOTX64.EFI配置 → QEMUでEFIを起動

**学んだこと**  
- Dockerイメージを使った環境構築をしたが、同じコマンドを叩くだけでスムーズな環境構築ができたので便利だった
- コンピュータが起動して動作をするまでの流れを再現したが、何やってるかわからなかった


### Day 9: 2025年5月5日

**今日の進捗**  
- LeetCodeの「Top Interview 150」を2問解いた
- 「ゼロからのOS自作入門」の第2回講義を受けた
- EDK II で UEFI アプリをビルドした

**学んだこと**  
- 途中でディレクトリが見つからないとエラーが出て時間がかかった
- ChatGPTに聞きながら、Hellow, Mikan World!が出力できたので良かった


### Day 10: 2025年5月6日

**今日の進捗**  
- LeetCodeの「Top Interview 150」を2問解いた
- 「ゼロからのOS自作入門」の第3回講義を受けた
- カーネルファイルを作成した
- 第1,2回講義の内容を教科書を見返したり調べたりしながら復習した

**学んだこと**  
- バイナリファイルを実行し、Hello, worldが画面に出力されるまでのファームウェアの処理が理解できた
- バイナリファイルを実行してHello, worldを表示する方法と、C言語で書いたプログラムを実行して表示する方法の違いを理解した


### Day 11: 2025年5月7日

**今日の進捗**  
- 東大松尾研究所の「深層学習 DeepLearning基礎講座 2025」の第4回講義課題を解いた
- 課題と別にサッカー選手の顔認識をするAIモデルを作って理解を深めた

**学んだこと**  
- パラメータの最適化, 初期化, 正規化, 正則化に関する手法を学んだ


### Day 12: 2025年5月8日

**今日の進捗**  
- LeetCodeの「Top Interview 150」を3問解いた

**学んだこと**  
- BFS, Greedy, H-Indexなどのテーマを学んだ


### Day 13: 2025年5月9日

**今日の進捗**  
- LeetCodeの「Top Interview 150」を1問解いた
- 「ゼロからのOS自作入門」の第4回講義を受けた

**学んだこと**  
- O(1)でリストに要素を追加、削除する方法を学んだ
- makeコマンドでビルド（コンパイル、リンク）を自動化する方法を学んだ


### Day 14: 2025年5月10日

**今日の進捗**  
- LeetCodeの「Top Interview 150」を2問解いた

**学んだこと**  
- O(1)で自身以外の要素を累積計算をする方法と貪欲法（Greedy）で探索する方法を学んだ


### Day 15: 2025年5月11日

**今日の進捗**  
- LeetCodeの「Top Interview 150」を2問解いた
- 「ゼロからのOS自作入門」の第5回講義を受けた

**学んだこと**  
- ツーポインタ法, Greedy（貪欲法）でブロックとブロックの間にある水の量を求める問題を解いた
- 両端から探索していく方法で解くやり方を学んだ


### Day 16: 2025年5月12日

**今日の進捗**  
- LeetCodeの「Top Interview 150」を2問解いた

**学んだこと**  
- 与えられた数字をローマ文字列に変換する問題を解いた
- ただ変換するだけでなく、特定の組み合わせは例外的に変換する必要があったので悩んだ


### Day 17: 2025年5月13日

**今日の進捗**  
- LeetCodeの「Top Interview 150」を2問解いた
- 「ゼロからのOS自作入門」の第6回講義（a,b）を受けた

**学んだこと**  
- 文字列操作の問題を解いた
    - 58. Length of Last Word（最後の単語の長さ）
    - 14. Longest Common Prefix（最長共通接頭辞）
- Easyレベルであればほぼ自力で回答できるようになってきた
- 構造体フィールド名の不一致により、EDK II 側で ビルドエラー発生
- PCIデバイスを検出するプログラムを理解した


### Day 18: 2025年5月15日

**今日の進捗**  
- LeetCodeの「Top Interview 150」を1問解いた
- 東大松尾研究所の「深層学習 DeepLearning基礎講座 2025」の第5回講義課題を解いた

**学んだこと**  
- CNNの実装について学んだ
- 文字列操作の問題を解いた
    - 151 Reverse Words in a String（Two Pointers, List/Stack Usage）
- 末尾から走査して単語を切り出すところまではあっていたがコードが冗長になってしまった
- 例外的なテストケースを考える前に、まず必要な処理からコードに落とし込んでいくことが重要だと思った
- 例えば、今回のケースだと末尾の空白を除去して最後の文字のインデックスを取得することが最初にやる作業なので、その実装に集中するなど


### Day 19: 2025年5月16日

**今日の進捗**  
- LeetCodeの「Top Interview 150」を2問解いた

**学んだこと**  
- 文字列操作の問題を解いた
    - 6 Zigzag Conversion
    - 28 Find the Index of the First Occurrence in a String


### Day 20: 2025年5月19日

**今日の進捗**  
- LeetCodeの「Top Interview 150」を2問解いた
- 「ゼロからのOS自作入門」の第6章（b, c）を終わらせた
- LearnSQL.comの「SQL Practice」を4問解いた

**学んだこと**  
- 文字列操作とポインタの問題を解いた
    - 125 Valid Palindrome
    - 68 Text Justification
- マウスの動きに合わせてカーソルを動かせるようになった
- OSがPCIデバイスを検知し、レジスタにアクセスするまでの流れを学んだ


### Day 21: 2025年5月20日

**今日の進捗**  
- LeetCodeの「Top Interview 150」を2問解いた
- LearnSQL.comの「SQL Basic」を22問解いた

**学んだこと**  
- ポインタの問題を解いた
    - 125 Valid Palindrome
    - 68 Text Justification
- 「SQL Basic」の以下の章を進めた
    - 5.More on JOINs (22/22)
- JOINメソッド（INNER, OUTER, RIGHT, LEFT）の使い方を理解した


### Day 22: 2025年5月21日

**今日の進捗**  
- LeetCodeの「Top Interview 150」を2問解いた

**学んだこと**  
- ポインタの問題を解いた
    - 111 Container With Most Water
    - 15 3Sum
- sortの使い所や3つ変数が必要なときのポインタの使い方を理解した


### Day 23: 2025年5月22日

**今日の進捗**  
- LeetCodeの「Top Interview 150」を2問解いた
- CNNを使ってサッカー選手の顔画像認識をするAIモデルを実装した（松尾研究所第5回講義の復習）
- LearnSQL.comの「SQL Basic」を22問解いた

**学んだこと**  
- sliding windowの問題を解いた
    - 3 Longest Substring Without Repeating Characters
    - 209 Minimum Size Subarray Sum
- set（集合型）で出現したかどうかを確認する方法を学んだ
- 「SQL Basic」の以下の章を進めた
    - 2.Selecting from one table (22/22)

### Day 24: 2025年5月23日

**今日の進捗**  
- LeetCodeの「Top Interview 150」を2問解いた
- 「ゼロからのOS自作入門」の第7章を終わらせた

**学んだこと**  
- sliding windowの問題を解いた
    - 30 Substring with Concatenation of All Words
    - 76 Minimum Window Substring
- 割り込み処理でマウスを動かす方法を学んだ
- ポーリングの代わりにFIFOを使うことで割り込みハンドラの処理をより速くした


### Day 25: 2025年5月25日

**今日の進捗**  
- LeetCodeの「Top Interview 150」を2問解いた

**学んだこと**  
- matrixの問題を解いた
    - 36 Valid Sudoku
    - 54 Spiral Matrix


### Day 26: 2025年5月26日

**今日の進捗**  
- LeetCodeの「Top Interview 150」を2問解いた
- 「ゼロからのOS自作入門」の第8章を終わらせた
- LearnSQL.comの「SQL Basic」を48問解いた


**学んだこと**  
- matrixの問題を解いた
    - 48 Rotate Image
    - 73 Set Matrix Zeroes
- メモリ管理について学んだ
- 物理メモリの使用状況を取得し、メモリの割り当てと解放をする方法を学んだ
- 「SQL Basic」の以下の章を進めた
    - 3.Querying more than one table (13/13)
    - 4.Aggregation and grouping (23/23)
    - 6.Subqueries (12/22)


### Day 27: 2025年5月27日

**今日の進捗**  
- LeetCodeの「Top Interview 150」を2問解いた
- 「ゼロからのOS自作入門」の第11章(a,b,c,d)を進めた


**学んだこと**  
- matrix, hashmapの問題を解いた
    - 289 Game of Life
    - 383 Ransom Note
- 複数のタイマを同時に作動させるために、LocalAPICタイマを周期動作させ割り込みを発生させた


### Day 28: 2025年5月28日

**今日の進捗**  
- LeetCodeの「Top Interview 150」を2問解いた

**学んだこと**  
- hashmapの問題を解いた
    - 205 Isomorphic Strings
    - 290 Word Pattern


### Day 29: 2025年5月29日

**今日の進捗**  
- LeetCodeの「Top Interview 150」を2問解いた
- 東大松尾研究所の「深層学習 DeepLearning基礎講座 2025」の第6回講義課題を解いた

**学んだこと**  
- hashmapの問題を解いた
    - 242 Valid Anagram
    - 49 Group Anagrams
- 物体検知とセグメンテーションについて学んだ


### Day 30: 2025年5月30日

**今日の進捗**  
- LeetCodeの「Top Interview 150」を2問解いた
- 「ゼロからのOS自作入門」の第11章(e), 13章, 14章（a,b）を進めた

**学んだこと**  
- hashmapの問題を解いた
    - 1 Two Sum
    - 202 Happy Number
- 複数のコンテキストを持つタスクをプリエンティブマルチタスクで並行処理できるようにした
- タスクの優先度をつけられるように実行状態、実行可能状態、待ち状態に分類させ、タスクに優先度レベルを設定した


### Day 31: 2025年5月31日

**今日の進捗**  
- LeetCodeの「Top Interview 150」を2問解いた
- 「ゼロからのOS自作入門」の14章（c,d）, 17章を終わらせた

**学んだこと**  
- hashmapの問題を解いた
    - 219 Contains Duplicate II
    - 128 Longest Consecutive Sequence
- ファイルシステムについて学んだ
- UEFI の Block I/O Protocolを使い、「ボリュームイメージ作成→EFI ブートローダーで読み込み→カーネルへ渡す」という一連の流れを実現した
- これを応用し、ターミナル上でlsコマンドが使えるようになった。


### Day 32: 2025年6月2日

**今日の進捗**  
- LeetCodeの「Top Interview 150」を2問解いた
- 「ゼロからのOS自作入門」の18章, 19章を終わらせた

**学んだこと**  
- Intervalsの問題を解いた
    - 228 Summary Ranges
    - 56 Merge Intervals
- FAT構造を理解しファイルをターミナル上で開くcatコマンドに対応するプログラムを実装した
- 実行可能ファイルをボリュームイメージに追加し計算機アプリケーションを実装した
- 仮想アドレスと物理アドレスを対応づけるページングについて学んだ

### Day 33: 2025年6月3日

**今日の進捗**  
- LeetCodeの「Top Interview 150」を2問解いた
- 「ゼロからのOS自作入門」の20章を終わらせた

**学んだこと**  
- Intervalsの問題を解いた
    - 57 Insert Interval
    - 452 Minimum Number of Arrows to Burst Balloons
- システムコールについて学んだ
- メモリアクセスに対して権限レベルを設定し、アプリが使えるOSの関数を制限する方法について学んだ

### Day 34: 6月5日

**本日の進捗**  
- LeetCodeのTop Interview 150から2問解いた  
- 東京大学松尾研の「Deep Learning Basics」講義第7回を学習した  

**学んだこと**  
- スタックに関する問題を解く練習をした：  
    - 20. Valid Parentheses  
    - 71. Simplify Path  
- RNNについて学んだ  
- 時系列データを使ってニューラルネットワークが文脈を保持する仕組みを理解した  


### Day 35: 6月6日

**本日の進捗**  
- LeetCodeのTop Interview 150から2問解いた  
- 「ゼロからの自作OS入門」のセクション1、2を完了した（2周目）  

**学んだこと**  
- スタックに関する問題を解く練習をした：  
    - 150. Evaluate Reverse Polish Notation  
    - 155. Min Stack  
- QEMUでBOOTX64.EFI（実行ファイル）を起動する方法を復習した  
- UEFIおよびEDK IIの機能を使ってメモリマップを取得した  
- ポインタについて基本的な理解を得た  
- 講義で使用されているコードを写経し、処理の流れを追って理解した  


### Day 36: 6月7日

**本日の進捗**  
- LeetCodeのTop Interview 150を2問解いた  
- 「ゼロからの自作OS入門」のセクション3aを完了した（2周目） 
-  Cisco Networking Academyの「Networking Basics」のModule1.1~1.3まで完了した

**学んだこと**  
- StackとLinked Listの問題を解いた:
    - 224 Basic Calculator
    - 141 Linked List Cycle
- UEFI のブートサービスを使ったメモリマップの取得について復習した
- ネットワークの概要について復習した


### Day 37: 6月9日

**本日の進捗**  
- LeetCodeのTop Interview 150を2問解いた  
- 「ゼロからの自作OS入門」のセクション3aを完了した（2周目） 
-  Cisco Networking Academyの「Networking Basics」のModule1.1~1.3まで完了した

**学んだこと**  
- Linked Listの問題を解いた:
    - 2 Add Two Numbers
    - 21 Merge Two Sorted Lists
- ピクセルを描画する方法を復習した
- ポインタについて、C++をコンパイルした結果をアセンブリ言語で見ながら理解した

### Day 38: 6月10日

**本日の進捗**
- LeetCodeのTop Interview 150から2問解いた
- 『ゼロからの自作OS入門』のセクション4(d)を完了した（2周目）

**学んだこと**
- Linked Listに関する問題を解いた:
    - 92 Reverse Linked List II
    - 138 Copy List with Random Pointer
- Linked Listのコピーと反転の方法を学んだ
- EFL形式のカーネルファイルをメモリにロードする方法を復習した

### Day 39: 6月11日

**本日の進捗**
- LeetCodeのTop Interview 150から1問解いた
- Cisco Networking Academyの「Networking Basics」コースのセクション1.4〜2.2を完了した

**学んだこと**
- Linked Listに関する問題を解いた:
    - 25 Reverse Nodes in k-Group
- Reverse Nodes in k-Groupの問題の解法を学んだ
- ネットワークコンポーネントと基本的な通信方式（P2Pおよびクライアント-サーバ方式）を復習した


### Day 40: 6月12日

**本日の進捗**
- LeetCodeのTop Interview 150から2問解いた
- 東京大学 松尾研究室の「Deep Learning Basics」コースの講義7の課題を提出した

**学んだこと**
- Linked Listに関する問題を解いた:
    - 19 Remove Nth Node From End of List
    - 82 Remove Duplicates from Sorted List II


### Day 41: 6月13日

**本日の進捗**
- LeetCodeのTop Interview 150から2問解いた
- 去年参加したインターンシップに関するQiitaの記事を編集した

**学んだこと**
- Linked Listに関する問題を解いた:
    - 86 Partition List
    - 61 Rotate List


### Day 42: 6月15日

**本日の進捗**
- LeetCodeのTop Interview 150から1問解いた
- 去年参加したインターンシップに関するQiitaの記事を編集した

**学んだこと**
- Linked Listに関する問題を解いた:
    - 146 LRU Cache
- ノードとハッシュテーブルを対応づけることで解くという方法を学んだ


### Day 43: 6月16日

**本日の進捗**
- LeetCodeのTop Interview 150から2問解いた
- 「Create Yor Own OS from Scratch」のセクション5を完了した（2周目）
- Cisco Networking Academyの「Exploring Networking with Cisco Packet Tracer」コースのモジュール1を完了した

**学んだこと**
- Binary Tree Generalに関する問題を解いた:
    - 104 Maximum Depth of Binary Tree
    - 100 Same Tree
- コンソールに文字列を出力する方法を復習した
- Cisco Packet Tracerを使ったネットワークの学習教材を探していたところ、参考になりそうなサイトを見つけた。
- このサイトかUdemyを使って、ネットワークの実践的な基礎を固めていきたい。

### Day 44: 6月17日

**本日の進捗**
- LeetCodeのTop Interview 150から2問解いた
- 「ゼロからのOS自作入門」の6章(a)を完了した（2周目）

**学んだこと**
- 二分木に関する問題を解いた:
    - 226 Invert Binary Tree
    - 101 Symmetric Tree

### Day 45: 6月19日

**本日の進捗**
- LeetCodeのTop Interview 150から2問解いた
- 松尾研の「深層学習基礎」講座の第8回の課題を提出した

**学んだこと**
- 二分木に関する問題を解いた:
    - 105 Construct Binary Tree from Preorder and Inorder Traversal
    - 106 Construct Binary Tree from Inorder and Postorder Traversal

### Day 46: 6月20日

**本日の進捗**
- LeetCodeのTop Interview 150から2問解いた
- 「ゼロからのOS自作入門」の6章(b)を進めた（2周目）

**学んだこと**
- 二分木に関する問題を解いた:
    - 117 Populating Next Right Pointers in Each Node II
    - 114 Flatten Binary Tree to Linked List

### Day 47: 6月21日

**本日の進捗**
- LeetCodeのTop Interview 150から2問解いた
- 「ゼロからのOS自作入門」の6章(b)を完了した（2周目）

**学んだこと**
- 二分木に関する問題を解いた:
    - 112 Path Sum
    - 129 Sum Root to Leaf Numbers

### Day 48: 6月22日

**本日の進捗**
- LeetCodeのTop Interview 150から1問解いた

**学んだこと**
- 二分木（一般）に関する問題を解いた:
    - 124 Binary Tree Maximum Path Sum

### Day 49: 6月23日

**本日の進捗**
- LeetCodeのTop Interview 150から2問解いた
- 「ゼロからのOS自作入門」の6章(c)を完了した（2周目）
- Udemyコース「The Complete Course on Cisco Packet Tracer」のセクション2を進めた

**学んだこと**
- 二分木（一般）に関する問題を解いた:
    - 173 Binary Search Tree Iterator
    - 222 Count Complete Tree Nodes
- シンプルなネットワークの構築を解いた:
    - 9 Basic Device Configurations

### Day 50: 6月24日

**本日の進捗**
- LeetCodeのTop Interview 150から2問解いた
- 「ゼロからのOS自作入門」の7章(a)を完了した（2周目）
- Udemyコース「The Complete Course on Cisco Packet Tracer」のセクション2, 3を進めた

**学んだこと**
- 二分木と幅優先探索に関する問題を解いた:
    - 236 Lowest Common Ancestor of a Binary Tree
    - 199 Binary Tree Right Side View
- シンプルなネットワーク構築、ルーティングの基礎、静的ルーティングについて練習した:
    - 9 Basic Device Configurations
    - 10 Cabling in Packet Tracer
    - 11 IP & Subnetting Assigning
    - 12 Lab with one switch and PCs
    - 14 Introduction to routing and routers
    - 15 Dynamic and Static routing

### Day 51: 6月26日

**本日の進捗**
- LeetCodeのTop Interview 150から2問解いた
- 松尾研の「深層学習基礎」講座の第8回課題を提出した
- Udemyコース「The Complete Course on Cisco Packet Tracer」のセクション3を進めた

**学んだこと**
- 二分木の幅優先探索（BFS）に関する問題を解いた:
    - 637 Average of Levels in Binary Tree
    - 102 Binary Tree Level Order Traversal
- シンプルなネットワーク構築、ルーティングの基礎、静的ルーティングについて練習した:
    - 16 Configuring static routing

### Day 52: 6月27日

**本日の進捗**
- LeetCodeのTop Interview 150から2問解いた
- 「ゼロからのOS自作入門」の7章(b)を完了した（2周目）

**学んだこと**
- 二分木の幅優先探索（BFS）と二分探索木に関する問題を解いた:
    - 103 Binary Tree Zigzag Level Order Traversal
    - 530 Minimum Absolute Difference in BST

### Day 53: 6月28日

**本日の進捗**
- LeetCodeのTop Interview 150から2問解いた
- 「ゼロからのOS自作入門」の8章(a)を完了した（2周目）

**学んだこと**
- 二分木の幅優先探索（BFS）と二分探索木に関する問題を解いた:
    - 230 Kth Smallest Element in a BST
    - 98 Validate Binary Search Tree

### Day 54: 6月30日

**本日の進捗**
- LeetCodeのTop Interview 150から2問解いた
- 「ゼロからのOS自作入門」の8章(b)を完了した（2周目）

**学んだこと**
- グラフの一般的な問題の練習をした:
    - 200 Number of Islands
    - 130 Surrounded Regions

### Day 55: 7月1日

**本日の進捗**
- LeetCodeのTop Interview 150から2問解いた
- 「ゼロからのOS自作入門」の8章(c)を完了した（2周目）
- Udemy講座「The Complete Course on Cisco Packet Tracer」のセクション4を進めた

**学んだこと**
- グラフの一般的な問題の練習をした:
    - 133 Clone Graph
    - 399 Evaluate Division
- スタティックルーティングとRIPの設定を解いた:
    - 18 Configuring static routing
    - 19 Configuring Rip

### Day 56: 7月3日

**本日の進捗**
- LeetCodeのTop Interview 150から2問解いた
- 「ゼロからのOS自自作入門」の11章(d)を完了した（2周目）
- Udemy講座「The Complete Course on Cisco Packet Tracer」のセクション4を進めた
- 松尾研の「深層学習基礎」講座の第10回課題を提出した

**学んだこと**
- グラフの一般的な問題の練習をした:
    - 207 Course Schedule
    - 210 Course Schedule II
- RIP、OSPF、EIGRPの設定を解いた:
    - 20 Configuring OSPF
    - 21 Configuring EIGRP
    - 22 Redistribution, Rip, OSPF & EIGRP

### Day 57: 7月4日

**本日の進捗**
- LeetCodeのTop Interview 150から2問解いた
- 「ゼロからのOS自自作入門」の13章(a)を完了した（2周目）
- Udemy講座「The Complete Course on Cisco Packet Tracer」のセクション5を進めた

**学んだこと**
- グラフのBFS問題を解いた:
    - 909 Snakes and Ladders
    - 433 Minimum Genetic Mutation
- VLANの設定を解いた:
    - 23 Intro duction to VLANs
    - 24 Configuration of VLANs

### Day 58: 7月5日

**本日の進捗**
- LeetCodeのTop Interview 150から2問解いた
- 「ゼロからのOS自自作入門」の13章(b)を完了した（2周目）

**学んだこと**
- グラフのBFS問題とTrie木の問題を解いた:
    - 127 Word Ladder
    - 208 Implement Trie (Prefix Tree)

### Day 59: 7月7日

**本日の進捗**
- LeetCodeのTop Interview 150から2問解いた
- 「ゼロからのOS自自作入門」の13章(c,d)を完了した（2周目）

**学んだこと**
- Trie木の問題を解いた:
    - 211 Design Add and Search Words Data Structure
    - 212 Word Search II

### Day 60: 7月8日

**本日の進捗**
- LeetCodeのTop Interview 150から2問解いた
- 「ゼロからのOS自自作入門」の14章(a)を完了した（2周目）
- Udemy講座「The Complete Course on Cisco Packet Tracer」のセクション5を進めた

**学んだこと**
- Backtrackingの問題を解いた:
    - 17 Letter Combinations of a Phone Number
    - 77 Combinations
- STPの設定について学んだ:
    - 26 Spanning Tree Protocol
    - 27 Port Security
    - 28 Configuration of Multi Switch network

### 61日目: 7月10日

**本日の進捗**
- LeetCodeのTop Interview 150から2問解いた
- 松尾研の「深層学習基礎」講座の第11回講義の課題を提出した

**学んだこと**
- Backtrackingの問題を解いた:
    - 46 Permutations
    - 39 Combination Sum

### 62日目: 7月11日

**本日の進捗**
- LeetCodeのTop Interview 150から2問解いた
- 「ゼロからのOS自作入門」の14章(b,c,d)を完了した（2周目）

**学んだこと**
- Backtrackingの問題を解いた:
    - 52 N-Queens II
    - 22 Generate Parentheses

### 63日目: 7月12日

**本日の進捗**
- LeetCodeのTop Interview 150から1問解いた
- Udemy講座「The Complete Course on Cisco Packet Tracer」のセクション6を進めた

**学んだこと**
- Backtrackingの問題を解いた:
    - 79 Word Search
- DHCP、DNS、NATの設定について学んだ:
    - 30 Introduction DHCP, DNS, NAT
    - 31 DHCP Configurations
    - 32 DNS Configuraitons
    - 33 NAT Configurations

### 64日目: 7月14日

**本日の進捗**
- Udemy講座「The Complete Course on Cisco Packet Tracer」のセクション6と7を進めた

**学んだこと**
- ACLの設定について学んだ:
    - 34 DHCP on Router
    - 36 Introduction to Network Security
    - 37 Standard and Extended ACLs

### 65日目: 7月15日

**本日の進捗**
- LeetCodeのTop Interview 150から3問解いた
- Udemy講座「The Complete Course on Cisco Packet Tracer」のセクション6を進めた

**学んだこと**
- 分割統治法と探索木の問題を解いた:
    - 148 Sort List
    - 108 Convert Sorted Array to Binary
    - 427 Construct Quad Tree

### 66日目: 7月17日

**本日の進捗**
- LeetCodeのTop Interview 150から2問解いた
- 松尾研の「深層学習基礎」講座の第12回講義の課題を提出した

**学んだこと**
- カダネのアルゴリズムの問題を解いた:
    - 23 Merge k Sorted Lists
    - 53 Maximum Subarray

### 67日目: 7月18日

**本日の進捗**
- LeetCodeのTop Interview 150から2問解いた
- Udemy講座「The Complete Course on Cisco Packet Tracer」のセクション7を進めた

**学んだこと**
- カダネのアルゴリズムの問題を解いた:
    - 918 Maximum Sum Circular Subarray
- VPNとファイアウォールの設定について学んだ:
    - 38 ACLs on based of Src/Dst Ips
    - 39 VPN on Cisco Router
    - 40 Cisco ASA Firewall Lab
    - 42 Introduction to Wireless Security Protocols

### 68日目: 7月19日

**本日の進捗**
- LeetCodeのTop Interview 150から2問解いた
- Udemy講座「The Complete Course on Cisco Packet Tracer」のセクション7を進めた

**学んだこと**
- 二分探索の問題を解いた:
    - 35 Search Insert Position
    - 74 Search a 2D Matrix
    - 162 Find Peak Element

### 69日目: 7月21日

**本日の進捗**
- LeetCodeのTop Interview 150から2問解いた
- Udemy講座「The Complete Course on Cisco Packet Tracer」のセクション7を進めた

**学んだこと**
- 二分探索の問題を解いた:
    - 33 Search in Rotated Sorted Array
    - 34 Find First and Last Position of Element in Sorted Array

### 70日目: 7月22日

**本日の進捗**
- LeetCodeのTop Interview 150から2問解いた
- Udemy講座「The Complete Course on Cisco Packet Tracer」のセクション8を進めた

**学んだこと**
- 二分探索の問題を解いた:
    - 33 Search in Rotated Sorted Array
    - 34 Find First and Last Position of Element in Sorted Array
- VPNとWi-Fiの設定について学んだ:
    - 43 Wireless Controller, Access points Configurations
    - 45 Common Network issues and Solutions
    - 46 Packet tracer simulation tool
    - 47 Network Optimization Tips

### 71日目: 7月24日

**本日の進捗**
- LeetCodeのTop Interview 150から2問解いた
- 松尾研の「深層学習基礎」講座の第13回講義の課題を提出した
- 松尾研の「深層学習基礎」講座の最終課題を提出した

**学んだこと**
- ヒープの問題を解いた:
    - 215 Kth Largest Element in an Array
    - 502 IPO

### 72日目: 7月25日

**本日の進捗**
- LeetCodeのTop Interview 150から2問解いた

**学んだこと**
- ヒープの問題を解いた:
    - 373 Find K Pairs with Smallest Sums
    - 295 Find Median from Data Stream