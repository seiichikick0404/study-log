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


