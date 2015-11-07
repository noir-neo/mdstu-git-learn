# \#MD勉強会 【デザイナーも使えると制作が810倍、チーム開発なら114514倍捗る Git 入門】

## アジェンダ

1. Git とは？
2. なぜデザイナーも Git?
3. Git の概念(概念だけだと結構難しいので基本部分だけさらっと)
4. 自分の PC で使えるようにしよう
5. とりあえず触ってみよう
6. 他人とソースコードを共有してみよう
7. 他人のソースコードに書き加えてみよう
8. まとめ・事後学習紹介


## Git とは？

* ソースコードの管理をするシステム(ソフトウェア)
  * 変更点がわかる
  * 他の人の作業とあとで合わせるのが楽
* リーナス・トーバルズが Linux 作るために作った
  * 似たようなことができるものは他にもある
    * 流行ってる

## なぜデザイナーも Git?

* [本当は怖くない！デザイナーがGitを大好きになった♡５つの理由](http://blog.nanapi.co.jp/tech/2014/04/23/git-love/)
* [【GGG#4】Aiming『ぐるぐるイーグル』にみるゲーム性を左右する背景マップの作り方…職種を超えた挑戦が効率的なワークフローを生む](http://gamebiz.jp/?p=151641)
* [怖くない！エンジニア以外のメンバに気持ちよく GitHub を使い始めてもらうには](http://techlife.cookpad.com/entry/2015/09/17/170158)


## Git の概念

難しいので基本だけさらっといくよ〜

### 基本

リポジトリ: Git 管理下のフォルダの事だと思ってOK

リポジトリを作ったら、変更点の中で加えたいのをガッと `add` して、 `commit` するだけ！

### ローカルとリモート

Dropbox とかと一緒で、手元のPCと、サーバー(と、また他のPC)があって、それで初めて共有できる、みたいな感じです。

### 郵便局メソッド

* https://speakerdeck.com/yunico/20140601-github-kaigi-yunico?slide=14
* http://qiita.com/yunico-jp/items/87bdd13971e82833f6bb


## 自分の PC で使えるようにしよう

### CLI vs GUI

### SourceTree のインストール

https://ja.atlassian.com/software/sourcetree/overview/

## とりあえず触ってみよう

### リポジトリを作る

### リポジトリ内に適当なファイルを作る

### add する

### commit する

### さっきのファイルに変更を加える

### diff を確認する

### add する

### commit する

### log を確認する

## 他人とソースコードを共有してみよう

### リモートリポジトリサービスに登録する

無料で使えるリモートリポジトリサービスはいくつかありますが、

[GitHub](https://github.com/)
プライベートリポジトリを使うには有料プランが必要(学生だと申請すれば無料枠がもらえる！)

[BitBucket](https://bitbucket.org/)
プライベートリポジトリも無料で使える。

GitHub がいろいろ便利でいい感じなので、 GitHub のアカウントを持っていない人はとりあえず作ってみましょう！


### リモートリポジトリを作る

### remote を登録する

### push する

## 他人のソースコードに書き加えてみよう

### clone する

### branch を切る

### ファイルに変更を加える

### diff を確認する

### add する

### commit する

### push する

### PR を作る

[EMOJI CHEAT SHEET](http://www.emoji-cheat-sheet.com/)

### PR コメントでレビューする

### PR をマージする


## まとめ・事後学習

* [LearnGitBranching](http://k.swd.cc/learnGitBranching-ja/)
  * コマンドの Git を試してみたければ、まずはこれ。
* [Git チュートリアルとトレーニング| Atlassian](https://www.atlassian.com/ja/git/)
  * 用語解説とか結構丁寧。 SourceTree 作ってる会社の記事です。
