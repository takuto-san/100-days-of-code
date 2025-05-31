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