---
title: "高機能テキストエディタ「Visual Studio Code」で現在表示しているファイル名やディレクトリ名をコピーする方法"
date: 2020-06-12T16:54:38+09:00
summary: "オープンソースのMicrosoft社製高機能テキストエディタ「Visual Studio Code」で、現在表示しているファイル名、拡張子付きファイル名、現在のフォルダ名をクリップボードにコピーする方法をご紹介いたします。"
categories: ["サービス／ソフト"]
tags: ["Windows", "Macintosh", "Visual Studio Code"]
url: "/how-to-copy-the-current-file-name-to-clipboard-for-visual-studio-code"
draft: false
---

{{< img src="2020-06-11-screenshot-00001.png" caption="" alt="Visual Studio Codeロゴ画像" >}}

オープンソースのMicrosoft社製高機能テキストエディタ「Visual Studio Code」で、現在表示しているファイル名、拡張子付きファイル名、現在のディレクトリ名（フォルダ名）をクリップボードにコピーする方法をご紹介いたします。

- {{< exlink href="https://code.visualstudio.com/" text="Visual Studio Code" >}}

Visual Studio Codeのインストールがまだお済みでない場合はUSBポータブル版もご検討ください。

USBポータブル版は、必要なファイルを一か所のフォルダで管理することができます。そのためUSBメモリーなどの記憶媒体に入れることでどこでも設定環境を再現できます。フォルダさえ保存しておけば、PCの購入やOSの再インストールなどの際にも簡単に設定環境を再現できます。

ただし、エクスプローラーの使い方やフォルダの管理がよくわからなかったり、余計なトラブルを避けたい場合は通常のインストーラー付Visual Studio Codeをインストールすることをおすすめいたします。

- {{< inlink hrnef="/how-to-install-visual-studio-code-for-windows" text="[Windows]USBボータブル版Visual Studio Codeをインストールする方法" >}}

## 拡張機能「Copy file name」をインストール

Visual Code Studioを起動して、メニューの「表示」から「拡張機能」をクリックしてください。

{{< img src="2020-06-12-screenshot-00008.png" caption="" alt="拡張機能検索画面" >}}

検索フォームに「Copy file name」と入力してエンターキーを押してください。

{{< img src="2020-06-12-screenshot-00009.png" caption="" alt="Copy file nameを検索した画面" >}}

「Copy file name」と作者の「Viktor Nemes」氏と表示されてる項目をクリックしてください。

「インストール」をクリックしてインストールしてください。

{{< img src="2020-06-12-screenshot-00010.png" caption="" alt="Copy file name" >}}

## 使い方

### ショートカットキー

 [Ctrl]+[Alt]+F（Mac OS Xでは[Cmd]+[Alt]+F）

- ファイル名のみをクリップボードにコピーします。

[Ctrl]+[Alt]+E（Mac OS Xでは[Cmd]+[Alt]+E）

- 拡張子付きファイル名をクリップボードにコピーします。

### 右クリックメニュー

Visual Studio Code上のエクスプローラーを表示して、ファイルやディレクトリを右クリックするとメニューに項目が表示されます。

{{< img src="2020-06-12-screenshot-00013.png" caption="" alt="右クリックメニュー画面" >}}

「Copy file name」は、ファイル名のみをコピーします。

「Copy file name with extensions」は、拡張子付きファイル名をコピーします。

ディレクトリを右クリックしても「Copy file name」と表示されますが、ディレクトリ名をコピーすることができます。

#### 実例

{{< gif src="copy-file-name-and-directory-name-for-visual-studio-code.gif" caption="" alt="コピー＆ペースの実例Gif動画" >}}

以上です。読んでいただきありがとうございました。
