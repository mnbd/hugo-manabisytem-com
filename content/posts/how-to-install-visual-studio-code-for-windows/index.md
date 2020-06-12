---
title: "Windowsのzip版（USB Portable版）Visual Studio Codeをインストールする方法"
date: 2020-06-10T23:45:11+09:00
summary: "Micorosoft社製テキストエディタ「Visual Studio Code」のzip版（USB起動版/Portable版）のインストール手順をご紹介いたします。"
categories: ["サービス／ソフト"]
tags: ["Windows", "Visual Studio Code"]
url: "/how-to-install-visual-studio-code-for-windows"
draft: false
---

{{< img src="2020-06-11-screenshot-00001.png" caption="" alt="Visual Studio Codeロゴ画像" >}}

Micorosoft社製テキストエディタ「Visual Studio Code」のzip版（USB起動版/Portable版）のインストール手順をご紹介いたします。

- {{< exlink href="https://code.visualstudio.com/download" text="Visual Studio Code" >}}

## Visual Studio Code とは

Micorsoft社製のオープンソースのテキストエディタです。

Windows版だけでなく、Macintosh版やLinux版もあります。

さまざまな機能を追加することができます。

主にプログラマ向けですが、文章作成するだけでも十分に利用価値のあるソフトウェアです。

## Portable（ポータブル）バージョンとは

USBメモリーに入れて持ち運べてどこでも使用できるように設定されたソフトウェアです。

必要なファイルはソフトウェアのフォルダ内にあり、レジストリに書き込まないとされます。（一部、レジストリに書き込むソフトウェアもあるようです）

通常のソフトウェアではインストールは対話式で行われ、アンインストールはOSのアンインストール機能から削除できます。

ポータブル版では自分で解凍し、不要の際には自分で削除する必要があります。

フォルダを保存しておけば、OSの再インストール時に再設定せずに使用することができます。

### 注意点

あらゆるファイル階層でVisual Code Sutdioを起動したい場合に環境変数（PATH）を設定する必要があったり、特定のファイルをエクスプローラーでダブルクリックして起動したい場合はファイルの関連付けを手動で行わなければならないことです。

## ファイルのダウンロード

{{< exlink href="https://code.visualstudio.com/download" text="Visual Studio Code" >}}からzip版ファイルをダウンロードします。ご自身のWindows環境に合わせて64bitか32bitをお選びください。

{{< img src="2020-06-10-screenshot-00013.png" caption="" alt="ダウンロードページ" >}}

## 任意の位置にファイルを解凍

ここでは、VSCode-win32-x64-1.45.1.zip(2020/06/11現在)を解凍し、任意の位置に解凍してください。

以下は解凍したフォルダの内容です。

{{< img src="2020-06-10-screenshot-00014.png" caption="" alt="フォルダの内容" >}}

## dataフォルダの作成

解凍したフォルダの中で右クリックして「新規作成」から「フォルダ」を選んでください。

{{< img src="2020-06-10-screenshot-00015.png" caption="" alt="新規作成メニュー" >}}

「data」フォルダを作成します。

{{< img src="2020-06-10-screenshot-00016.png" caption="" alt="dataフォルダの作成" >}}

## Visual Studio Codeの起動

code.exeをダブルクリックしてください。

{{< img src="2020-06-10-screenshot-00017.png" caption="" alt="Visual Studio Code画面" >}}

以上です。読んでいただきありがとうございました。
