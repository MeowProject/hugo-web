+++
author = "ゆうと"
date = 2021-10-29T09:03:00Z
description = "MeowCodeによるHugoを設定する方法！"
image = "/images/group-2.png"
image_webp = "/images/group-2.webp"
title = "HUGOの設定方法"

+++
## これらの簡単な手順に従ってHUGOをインストールします。

### 1：Hugoのインストール

以下のリンクをチェックして、あなたのコンピュータにHugoをインストールしてください。
[HUGO](https://gohugo.io/getting-started/installing/)

### 2：あなたのプロジェクトを作成します

Hugoは新しいウェブサイトを作成するための新しいコマンドを提供します。

$ hugo new site meowcode （あなたはあなたのプロジェクト名にMeowCodeを置き換えることができます）

### 3：テーマをインストールします

ここでテーマを検索できます [THEME](https://hugothemesfree.com/)

そしてあなたもテーマを作ることができます！

$ cd theme && hugo new theme

### 4：ローカルにホスト

次のコマンドを使用してローカルにWebサイトを起動します。

$ hugo server

ウェブサイトに行く：

`http://localhost:1313`

### 5：基本構成

Webサイトを構築するには、--themeオプションを使用してテーマを設定できます。ただし、設定ファイル（config.toml）を変更してデフォルトとしてテーマを設定することをお勧めします。

![](https://cdn.discordapp.com/attachments/689337226123149336/903504952679354478/unknown.png)

### 6：最初のコンテンツページを作成します

hugo new blog/新しい投稿.md

また、あなたは使用することができます [FORESTRY](https://forestry.io/)

### 7：ウェブサイトを構築します

サイトの展開準備ができたら、次のコマンドを実行します。

hugo

### このコマンドを使用して、ミニフィールドバージョンを作成することもできます。

hugo–minify

あなたのWebサイトのすべての静的コンテンツとアセットを含むパブリックフォルダが生成されます。これで任意のWebサーバーにデプロイできます。
