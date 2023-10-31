---
theme: "penguin"
colorSchema: "auto"
layout: intro
# https://sli.dev/custom/highlighters.html
highlighter: shiki
title: Slidev Penguin Theme
fonts:
  mono: "PT Mono"
  sans: ["Open Sans", "Zen Kaku Gothic New"]
  serif: "PT Serif"
themeConfig:
  eventLogo: "https://github.com/fluidicon.png"
  eventUrl: "https://github.com/nntto/LT-202321030"
  twitter: "@NnttoDev"
  twitterUrl: "https://twitter.com/NnttoDev"
---

## コマンドランチャーで始める生産性向上術

---
layout: presenter
presenterImage: '/icon.png'
---

# 自己紹介

- 名前：志田
- 出身・現在地：札幌
- 趣味：行ったことのない場所に行くこと
  - 知らない街, 山, 海，歴史的建造物
- 最近のニュース
  - 自作キーボードデビューしました（keyball）

---

# コマンドランチャー, 使ってますか？

コマンドランチャーとは，<br>キーストロークのみでPC上の様々な操作を行えるようにするアプリケーションのこと．

例えば，以下のようなアプリが有名です．
- [PowerToys (Windows)](https://learn.microsoft.com/ja-jp/windows/powertoys/)
- [ueil (Windows)](https://ueli.app/#/)
- [Spotlight (Mac標準)](https://support.apple.com/ja-jp/guide/mac-help/mchlp1008/mac)
- [Raycast (Mac)](https://www.Raycast.com/)
- [Alfled (Mac)](https://www.alfredapp.com/)

---
layout: text-image
media: '/Raycast.png'
---

# おすすめは Raycast

なぜ？
- 基本無料
- UI/UXが良い
  - 見た目が良い
  - 操作が直感的で分かりやすく，簡単
  - 設定画面が分かりやすい
- プラグインを自作可能
- コミュニティ作成のプラグインが充実
- 注意：Mac のみ

---
layout: new-section
---

#  コマンドランチャーの基本機能を紹介

ここから先は Raycast の機能を紹介していきますが，<br>コマンドランチャーの基本機能はどのアプリもほぼ同じです．  
他のアプリケーションを選んでも，同等の体験が得られるはず（多分）

<div align="center">
<img src="/Raycast.png" style="width: 40%">
</div>

---
layout: text-image
media: '/Raycast search bar.png'
---

# Search Bar

Raycast を起動すると,  
まず，Search Bar が表示される．

Raycast の基本的な使い方は，Search Bar から  
コマンドを検索して実行すること．

以下のようなコマンドがある．
- アプリの検索と起動
- ファイルの検索
- システム機能の利用
- リンクを開く
- スニペットの作成と利用
- クリップボード履歴の管理
- ウィンドウ位置の管理
- プラグインで追加したコマンド

---
layout: new-section
---

# コマンドの紹介

アプリの検索と起動

ファイルの検索

システム機能の利用

リンクを開く

プラグイン

---

# アプリの検索と起動

1. アプリケーション名を検索 2. Enter を押す

<div align="center">
<img src="/open app 1.png" style="width: 50%">
</div>

---

# アプリの検索と起動

1. アプリケーション名を検索 2. Enter を押す

<div align="center">
<img src="/open app 2.png" style="width: 75%">
</div>


---

# ファイルの検索

1. Search Files コマンドを実行 2. キーワードを入力 3. Enter を押す
<div align="center">
<img src="/file search 1.png" style="width: 50%">
</div>

---

# ファイルの検索

1. Search Files コマンドを実行 2. キーワードを入力 3. Enter を押す
<div align="center">
<img src="/file search 2.png" style="width: 50%">
</div>
---

# システム機能の利用

1. システム機能を検索 2. Enter を押す

例えば，
シャットダウン，再起動，スリープ，ゴミ箱を空にする，音量を上げる，下げる，etc...  

<div align="center">
<img src="/Raycast systems.png" style="width: 50%">
</div>

---

# リンクを開く

リンクを検索 → Enter を押す
<div align="center">
<img src="/open link 1.png" style="width: 50%">
</div>

---

# リンクを開く

リンクを検索 → Enter を押す
<div align="center">
<img src="/open link 2.png" style="width: 75%">
</div>

---


# リンクを開く: クエリを渡す．

リンクにクエリを渡すことが可能  
例： Google で"Raycast"を検索．("Search Google" を実行 → 検索クエリ"Raycast"を入力 → Enter を押す)

<div align="center">
<img src="/search 1.png" style="width: 50%">
</div>

---

# リンクを開く: クエリを渡す．

リンクにクエリを渡すことが可能  
例： Google で"Raycast"を検索．("Search Google" を実行 → 検索クエリ"Raycast"を入力 → Enter を押す)

<div align="center">
<img src="/search 2.png" style="width: 50%">
</div>

---

# リンクを開く: クエリを渡す．

リンクにクエリを渡すことが可能  
例： Google で"Raycast"を検索．("Search Google" を実行 → 検索クエリ"Raycast"を入力 → Enter を押す)

<div align="center">
<img src="/search 3.png" style="width: 75%">
</div>

---

# リンクを開く: クエリを渡す．

様々な情報を Raycast という一つのインターフェースから検索することができる，かなり便利．

<div align="center">
<img src="/Raycast searches.png" style="width: 65%">
</div>

---

# プラグイン (Extensions)

Raycast には，コミュニティーによって開発された1200以上のプラグインが存在する．  
簡単インストールですぐに利用可能！
欲しいコマンドがなければ，自分で開発してもOK！


<div align="center">
<img src="/Raycast extensions.png" style="width: 65%">
</div>

---

# プラグイン (Extensions)

例を一つだけ紹介

---

# プラグイン (Extensions): GitHub

Raycast 上で Issue を立てられます

<div align="center">
<img src="/github issue.png" style="width: 70%">
</div>

---

# プラグイン (Extensions): GitHub

Raycast 上で通知を確認できます．

<div align="center">
<img src="/github notifications.png" style="width: 70%">
</div>

---

# プラグイン (Extensions): GitHub

Raycast 上で Workflow の実行履歴を確認できます．

<div align="center">
<img src="/github workflow.png" style="width: 70%">
</div>

---

# まとめ

コマンドランチャーは生産性向上に役立つ．

自在にカスタマイズして，自分の作業に合わせた環境を作ろう！