# study-log

# 2023 10/15

## やったこと

### LeetCode復習(二分探索・木構造)

[LeetCode - The World's Leading Online Programming Learning Platform](https://leetcode.com/problems/search-in-rotated-sorted-array/description/)

[Binary Tree Preorder Traversal - LeetCode](https://leetcode.com/problems/binary-tree-preorder-traversal/description/)

[Binary Tree Inorder Traversal - LeetCode](https://leetcode.com/problems/binary-tree-inorder-traversal/description/)

[LeetCode - The World's Leading Online Programming Learning Platform](https://leetcode.com/problems/diameter-of-binary-tree/)

[Binary Tree Postorder Traversal - LeetCode](https://leetcode.com/problems/binary-tree-postorder-traversal/description/)

### Backend Project3
  - EC2インスタンスの作成
  - コンソールからaws EC2にSSH接続
  - Git hubのSSH接続
  - 本番環境にNginxインストール
  - パブリックIPアクセス時にNginxの初期画面を表示


# 2023 10/16

## やったこと

### LeetCode(木構造)

[Balanced Binary Tree - LeetCode](https://leetcode.com/problems/balanced-binary-tree/description/)

[Same Tree - LeetCode](https://leetcode.com/problems/same-tree/description/)

### Backend Project3
  - ウェブサイトのホスト
  - ディレクトリの作成
  - 権限の割り当て
  - シンボリックリンクの作成
  - NGINX のアクセス権限の設定
    
**Static Web Servers　進行度70%**
    
## 学習方針

- 実務であまり触れられないインフラ周りをプロジェクト3で補完
- 完了したらDockerでの構築もやってみる


# 2023 10/17

## やったこと

### LeetCode(木構造)

[Subtree of Another Tree - LeetCode](https://leetcode.com/problems/subtree-of-another-tree/description/)

[Lowest Common Ancestor of a Binary Search Tree - LeetCode](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/description/)

### Backend Project3
  - NGINXの設定(サイトのデフォルト表示設定)
      - /etc/nginx/sites-available/defaultがNginxの設定ファイル
      - root /var/www/html;　←がデフォルトのルートパス
  - Filezillaのインストール
  - FilezillaでEC2インスタンスに接続
  - フリー素材を本番のmediaフォルダに送信
      - SFTPで通信を暗号化して送信(FTPをSSH接続で送信する仕組み)
  - ウェブサーバのドメインについてのインプット
    
    **Static Web Servers　進行度84%**
    
## 学習方針
  - 実務であまり触れられないインフラ周りをプロジェクト3で補完
  - 完了したらDockerでの構築もやってみる


# 2023 10/18

## やったこと

- LeetCode(木構造)

[Validate Binary Search Tree - LeetCode](https://leetcode.com/problems/validate-binary-search-tree/description/)

[Kth Smallest Element in a BST - LeetCode](https://leetcode.com/problems/kth-smallest-element-in-a-bst/description/)

### Backend Project3(**進行度86%**)
  - 独自ドメインの取得(お名前.com)
  - DNS設定
      - サブドメイン設定
  - ドメイン名で出力先を変更(Nginxの設定)
    
## 課題

- シンボリックリンクについて理解が曖昧
- LeetCodeのMedium以上になると正答率が一気に下がる(ある程度パターンを網羅しなきゃダメかも)
- atcoderの問題にも取り組みたい
- 技術質問対策も少しずつ進めたい


# 2023 10/19

## やったこと

### LeetCode(木構造)

[Count Good Nodes in Binary Tree - LeetCode](https://leetcode.com/problems/count-good-nodes-in-binary-tree/description/)

[Construct Binary Tree from Preorder and Inorder Traversal - LeetCode](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/description/)

### Backend Project3(**進行度100%**)
  - TLSの概要学習
  - TLSの設定
  - snapインストール(ubuntuのパッケージ管理)
  - Certbotインストール(Lets EncryptをCLIから使える)
  - TLS 認証を処理
    
## 課題
- レジェメ用のページ作成
- TLSの仕組みを口頭で説明できるようにする(面接対策)


# 2023 10/19

## やったこと

### AtcoderB問題
[B - 81](https://atcoder.jp/contests/abc144/tasks/abc144_b)
[B - Count ABC](https://atcoder.jp/contests/abc150/tasks/abc150_b)
[B - ATCoder](https://atcoder.jp/contests/abc122/tasks/abc122_b)

## 課題
- AtCorderのA~C問題レベルを確実に解けるようしたい(コーディングテストで多いらしい)
- まずは茶色コーダー目指す


# 2023 10/20

## やったこと

### Atcoderのコンテストに参加

## 課題
- A,B問題を15分以内に解く
- 簡単なC問題は解けるようにする
- オンラインコーディングテストは競プロに近い問題らしい？


# 2023 10/23

## やったこと

## AtcoderB問題

[B - 105](https://atcoder.jp/contests/abc106/tasks/abc106_b)
[B - Uneven Numbers](https://atcoder.jp/contests/abc136/tasks/abc136_b)

## カジュアル面談1件

- 人事だけだったので技術的な会話はできなかった
- 選考は人事・エンジニアとの面接とCTOとの面接で決定
- コーディングテストは無いらしい

## 課題

- まずは一番出題率が高い全探索問題周りから潰す
- Recursionプロジェクトのレジェメページを作成するか検討
- 面談は緊張すると会話が途切れてしまうので場数を増やしたい

# 2023 10/24

## やったこと

## Atcoder B・C問題

[B - K-th Common Divisor](https://atcoder.jp/contests/abc120/tasks/abc120_b)
[C - Digits in Multiplication](https://atcoder.jp/contests/abc057/tasks/abc057_c)
[C - Half and Half](https://atcoder.jp/contests/arc096/tasks/arc096_a)

## Backend Project3

- 本番環境にレジェメディレクトリを作成
- ポートフォリオ作成用の無料HTMLテンプレートの取得

## 課題

- AtCoderのC問題の正答率が低い
- Nginxの設定周りがあまり理解できてないので別途で調査する
- アルゴリズム対策としてLeetCodeも継続する


# 2023 10/26

## やったこと

## Atcoder B問題

[B - Measure](https://atcoder.jp/contests/abc319/tasks/abc319_b)

## Backend Project3

- シンボリックリンクのバグを解消
    - sudo rm /etc/nginx/sites-enabled/resume.seiprojectsを実行して解決できた
    - sudo nginx -tコマンドで構文エラーを検出できる ← これで問題箇所の特定ができた
- DNSリソースレコードの設定
    - レジェメ用のドメインを再設定
- TLS対応(SSL化)

下記がレジェメ用のページ

[WebデザイナーTARO YAMADA ポートフォリオ](https://resume.seiprojects.com/)

## 課題

- AtCoderの問題が思いのほか解けない
    - ある程度の慣れと競プロの技術書で対応
- テンプレートを自分用に変更する

# 2023 10/27

## やったこと

## Atcoder B問題

[B - Overlapping sheets](https://atcoder.jp/contests/abc318/tasks/abc318_b)

[B - Cutoff](https://atcoder.jp/contests/abc321/tasks/abc321_b)

## Backend Project3

- 作成したサイトに成果物を掲載

下記がレジェメ用のページ

[WebデザイナーTARO YAMADA ポートフォリオ](https://resume.seiprojects.com/)

## 課題

- 職務経歴書作成次第、PDFでDLできるリンクを追加
- あくまでバックエンドなので見た目は本当に最低限のところで止める
- デプロイを簡略化したい
  - 今は本番サーバにSSH接続してgit pull コマンドで更新してるため


# 2023 10/28

## やったこと

## AtCoder復習

[C - Peak](https://atcoder.jp/contests/abc326/tasks/abc326_c)

[B - Count ABC](https://atcoder.jp/contests/abc150/tasks/abc150_b)

[C - Peak](https://atcoder.jp/contests/abc326/tasks/abc326_c)

[B - ATCoder](https://atcoder.jp/contests/abc122/tasks/abc122_b)

## Backend Project3

- デプロイの自動化(GitHub Actions)
    - リポジトリでシークレットキー設定
        - SERVER_HOST(サーバーのIPアドレス)
        - SERVER_USERNAME(SSHログイン時のユーザー名)
        - SSH_PRIVATE_KEY(秘密鍵パス .pemファイルの中身全て)
    - ymlファイルに自動化したい処理を記述する
        - 今回の場合はmainブランチの更新をトリガーにしてサーバにSSH接続をしてPJディレクトリに移動しgit pull origin mainを実行

## 課題・感想

- Backend Project3はレジェメができたらDLできるようにする(一旦完成)
- Atcoderのコンテストを受けたら翌日に必ず復習しておく(A~C)
- 次はBackend Projectは4をやるか2をやるか迷う


# 2023 10/30

## やったこと

## AtCoder復習

[B - MissingNo.](https://atcoder.jp/contests/abc317/tasks/abc317_b)

[B - The Middle Day](https://atcoder.jp/contests/abc315/tasks/abc315_b)

## Backend Project4

- PHPの基礎確認

## 課題・感想

- 結構OOPでの開発メイン？っぽいので現状の優先度としては低いかも？
とはいえインフラ周りの学習はもう少しやりたいので進めてみる
- 職務経歴書の作成を少しずつ進めていきたい

# 2023 10/31

## やったこと

## AtCoder

[B - Roulette](https://atcoder.jp/contests/abc314/tasks/abc314_b)

[B - Who is Saikyo?](https://atcoder.jp/contests/abc313/tasks/abc313_b)

## Backend Project4

- PHPの基礎確認
- Food Service SimulationはOOPメインなので飛ばす

## カジュアル面談

- ゲームメディア運営
- 親会社はメガベン規模(上場してる)みたい
- 今回来たオファーはその子会社で開発規模は小規模

## 課題・感想

- 時間も限られてるのでバックエンドプロジェクトも必要な部分のみに絞る
- 良さげな企業はどんどんアポとってカジュアル面談していく
- 転職エージェントやユートラスト？も始めてみる


# 2023 11/1

## やったこと

## AtCoder

[B - TaK Code](https://atcoder.jp/contests/abc312/tasks/abc312_b)

[B - Vacation Together](https://atcoder.jp/contests/abc311/tasks/abc311_b)

## Backend Project4

- ****Restaurant Chain Mockup****
    - Git HubのリポジトリをSSH設定(ここで結構ハマった)
    - フォルダ構成の作成
    - 各クラスにプロパティを設定

## GitHubのSSH接続のエラー

**事象**

→ ローカルからリモートリポジトリにpushできるようにSSHキーを作成してgit cloneをしたところエラーが発生

**原因**

→ 接続先のサーバーが正当であることを確認するためのホストキーが変更されたため整合性が取れなくなった。
このホストキーは特定のサーバーと接続する際に**`known_hosts`**ファイルに保存されるため過去にGitHubのSSHキーを設定して、今回新たに作成し直したことでエラーが発生した。
known_hostsファイルの古い記述を削除して、新たなホストキーを設定して解決

## 技術質問対策

**3ウェイハンドシェイクとは何か？**

- TCP接続をする際に行う通信処理
- クライアントがsynパケットを送信(シーケンス番号)
- サーバがsynパケット内のシーケンス番号に+1をして自身のシーケンス番号を作成しACKパケットとして送信
- クライアントがそれぞれのシーケンス番号に+1をして送信して完了

上記を良い感じにまとめて伝える

## 課題・感想

- 時間も限られてるのでバックエンドプロジェクトも必要な部分のみに絞る
- 良さげな企業はどんどんアポとってカジュアル面談していく
- 転職エージェントやユートラスト？も始めてみる


# 2023 11/2

## やったこと

## AtCoder

[B - Strictly Superior](https://atcoder.jp/contests/abc310/tasks/abc310_b)

[B - Rotate](https://atcoder.jp/contests/abc309/tasks/abc309_b)

## 技術質問対策

## **YOUTRUST登録**

- 最低限のプロフィール入力
- レジェメを載せた


# 2023 11/3

## やったこと

## AtCoder

[B - Default Price](https://atcoder.jp/contests/abc308/tasks/abc308_b)

[B - racecar](https://atcoder.jp/contests/abc307/tasks/abc307_b)

[B - Base 2](https://atcoder.jp/contests/abc306/tasks/abc306_b)

[B - ABCDEFG](https://atcoder.jp/contests/abc305/tasks/abc305_b)

## BackendProject4

- ****Restaurant Chain Mockup****
    - 従業員データ出力
    - FileConvertibleインターフェースを実装
    - 全てのクラスのプロパティを設定

## 課題・感想

- ****Restaurant Chain Mockupは****20時間以内に終わらせたい
- AtCoderのマス目問題が苦手なので必ず復習する


# 2023 11/4

## やったこと

## AtCoder 復習

[B - Count ABC](https://atcoder.jp/contests/abc150/tasks/abc150_b)

[B - ATCoder](https://atcoder.jp/contests/abc122/tasks/abc122_b)

[B - Uneven Numbers](https://atcoder.jp/contests/abc136/tasks/abc136_b)

[B - 105](https://atcoder.jp/contests/abc106/tasks/abc106_b)

[B - K-th Common Divisor](https://atcoder.jp/contests/abc120/tasks/abc120_b)

## BackendProject4

- ****Restaurant Chain Mockup****
    - 従業員データ出力
    - FileConvertibleインターフェースを実装
    - 全てのクラスのプロパティを設定

## 課題・感想

- ****Restaurant Chain Mockupは****20時間以内に終わらせたい
- AtCoderのマス目問題が苦手なので必ず復習する

# 2023 11/5

## やったこと

## AtCoder 復習

[B - Measure](https://atcoder.jp/contests/abc319/tasks/abc319_b)
[C - Half and Half](https://atcoder.jp/contests/arc096/tasks/arc096_a)
[C - Digits in Multiplication](https://atcoder.jp/contests/abc057/tasks/abc057_c)


# 2023 11/13

## やったこと

## AtCoder
[B - ASCII Art](https://atcoder.jp/contests/abc294/tasks/abc294_b)
[B - Bombs](https://atcoder.jp/contests/abc295/tasks/abc295_b)

## BackendProject4

- ****Restaurant Chain Mockup****
    - スタイリングの調整
    - リファクタリング
        - docコメントの追加
        - ゲッターの追加

## 課題・感想

- 先週は学習時間が取れなかったので今週で取り返す


# 2023 11/14

## やったこと

## AtCoder

 

## BackendProject4

- ****Restaurant Chain Mockup 拡張版****
    - フォーム画面の作成
    - POST値のバリデーション適用

## 課題・感想

- チーム開発までにバックエンドプロジェクト4の完成
- 面接対策のための予定立てる


# 2023 11/15

## やったこと

## AtCoder

[B - Trimmed Mean](https://atcoder.jp/contests/abc291/tasks/abc291_b)
[B - Call the ID Number](https://atcoder.jp/contests/abc293/tasks/abc293_b)

## BackendProject4

- ****Restaurant Chain Mockup 拡張版****
    - 拡張に伴いRondomGanarageクラスを拡張
    - 各クラス(User, RestaurantChain, Location)の拡張
    - 入力値に合わせてオブジェクト生成

## 課題・感想

- JSON形式やマークダウンの形式での出力方法
- 転職エージェントに登録してみる

# 2023 11/16

## やったこと

## AtCoder

[B - Qual B](https://atcoder.jp/contests/abc290/tasks/abc290_b)

[B - Trimmed Mean](https://atcoder.jp/contests/abc291/tasks/abc291_b)

[B - V](https://atcoder.jp/contests/abc289/tasks/abc289_b)

## BackendProject4

- マークダウン形式に対応
- json形式のダウンロード
- テキスト形式のダウンロード
- HTML形式で出力

## 課題・感想

- リファクタリングが必要
- 職務経歴書作成

# 2023 11/17

## やったこと

## AtCoder

[B - Cat](https://atcoder.jp/contests/abc286/tasks/abc286_b)
[B - Postal Card](https://atcoder.jp/contests/abc287/tasks/abc287_b)
[B - Qualification Contest](https://atcoder.jp/contests/abc288/tasks/abc288_b)

## BackendProject4

- リファクタリング
    - 不要な記述やimportを削除
    - インデント修正
    - 責務の分離(主に関数)
    - Docコメントを追記
- README作成

## 課題・感想

- バリデーションやテストコードは追加しても良いかも

# 2023 11/17

## やったこと

## AtCoder

[B - Cat](https://atcoder.jp/contests/abc286/tasks/abc286_b)

[B - Postal Card](https://atcoder.jp/contests/abc287/tasks/abc287_b)

[B - Qualification Contest](https://atcoder.jp/contests/abc288/tasks/abc288_b)

## BackendProject4

- リファクタリング
    - 不要な記述やimportを削除
    - インデント修正
    - 責務の分離(主に関数)
    - Docコメントを追記
- README作成

## 課題・感想

- バリデーションやテストコードは追加しても良いかも

# 2023 11/17

## やったこと

## AtCoder(復習)

[B - Who is Saikyo?](https://atcoder.jp/contests/abc313/tasks/abc313_b)

[B - Roulette](https://atcoder.jp/contests/abc314/tasks/abc314_b)

[B - The Middle Day](https://atcoder.jp/contests/abc315/tasks/abc315_b)

[](http://er.jp/contests/abc317/tasks/abc317_b)

[B - Cutoff](https://atcoder.jp/contests/abc321/tasks/abc321_b)

## BackendProject4

- .gitignore設定
- 依存関係のインストール(PHP, comporser)
- シンボリックリンクの設定
- リバースプロキシの設定
    
    

## 課題・感想

- TLS設定
- サブドメイン設定のハンズオン作成
