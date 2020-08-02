---
title: "Visual Studio Codeで半角や全角の空白、行頭、行末を見えやすく表示する方法"
date: 2020-08-02T13:20:29+09:00
summary: "Visual Studio Codeで半角や全角の空白、行頭、行末を見えやすく表示する方法をご紹介いたします。"
categories: [""]
tags: ["Visual Studio Code（ビジュアルスタジオコード）の使い方", "拡張機能"]
url: "/how-to-use-whitespace-plus-for-visual-studio-code"
draft: false
---

{{< img src="/images/software/vscode.png" caption="" alt="VS Codeのアイコン画像" >}}

- 動作検証バージョン：Windows 10 Home（64bit、バージョン：1909、OSビルド：18363.900）＋Visual Studio Code（バージョン：1.46.1）＋Whitespace+（バージョン：0.0.5）

Visual Studio Code（以下、VS Code）でプログラムや文章を書いていて、空白や行頭、行末を視覚的にパッと認識したいと思うことはありませんか？

ここでは拡張機能「Whitespace+」を利用して、それらを見えやすく表示する方法をご紹介いたします。

## Visual Studio Codeとは

テキスト（文字情報）のみのファイルを作るためのソフトウェアです。類似ソフトにワードなどがあげられますが、ブラウザのように拡張機能をインストールすることで自分好みにカスタマイズできます。

VS Codeは、本来プログラマー向けのオープンソースソフトウェアですが、文章を書くための拡張機能も登場しており、プログラマーではない人が使用してもメリットがあります。

VS Codeのインストールについては以下の記事もご覧になってい見てください。
- {{< inlink nhref="https://manabisystem.com/how-to-install-visual-studio-code-for-windows/" text="Windowsのzip版（USB Portable版）Visual Studio Codeをインストールする方法" >}}

## Whitespace+とは

表示されているファイルの半角空白、全角空白、行頭、行末を表示してくれる拡張機能です。

表示非表示の切り替えや色、見え方の変更なども可能です。

## Whitespace+のインストール手順

1. VS Codeを起動して、メニューの［ファイル］ー［ユーザー設定］ー［拡張機能］を選択してください。  
{{< img src="2020-08-02-screenshot-00001.png" caption="" alt="ファイルメニュー画面" >}}

2. 検索ボックスに「Whitespace+」と入力して［Enter］キーを押してください。Whitespace+の項目が表示されますのでそこをクリックしてください。  
{{< img src="2020-08-02-screenshot-00002.png" caption="" alt="拡張機能検索ボックス" >}}

3. Whitespace+の概要説明が表示されたら［Install］ボタンをクリックしてください。  
{{< img src="2020-08-02-screenshot-00003.png" caption="" alt="Whitespace+概要画面" >}}

## Whitespace+の使い方

1. 空白を表示したいファイルを開いた状態で、［Ctrl］＋［Shift］＋［P］キーを押してください。画面上部に表示されたフォームへ「Whitetoggle」と入力すると「Whitespace+ Toggle」という項目が最上部に表示されますので［Enter］キーを押してください。
{{< img src="2020-08-02-screenshot-00006.png" caption="" alt="コマンドパレット画面" >}}

2. 開いているファイルの空白と行頭、行末が表示されます。  
{{< img src="2020-08-02-screenshot-00007.png" caption="" alt="空白、行頭、行末を表示した画面" >}}

## Whitespace+のカスタマイズ

1. ［Ctrl］＋［Shift］＋［P］キーを押して、画面上部に表示されたフォームへ「Whitespaceconfig」と入力すると「Whitespace Config」という項目が最上部に表示されますので［Enter］キーを押してください。

2. config.jsonファイルが開きます。  
{{< img src="2020-08-02-screenshot-00009.png" caption="" alt="config.json画像" >}}

{{< warning title="" text="Whitespace＋のカスタマイズはテキストファイルを編集することで可能です。テキストファイルが決まった書式で書かれていない場合、エラーで動作しなくなったり、適切な動作をしなくなったりしますので、これらの原理がよくわからない方はカスタマイズをしないことをオススメします。" >}}

### ファイルを開いた時にWhitespace+を適用

1. config.jsonファイルの3行目を以下のように書き換えてください。  
```config.json
"autoStart": true,
```
2. config.jsonファイルを保存してVS Codeを再起動してください。

### 表示スタイルの変更

- 空白（space）、タブ（tab）、行頭（newline）、行末（trailing）の各要素の表示スタイルを変更してください。表示幅などのピクセル数、カラーはRGBA形式で指定してください。  
{{< img src="2020-08-02-screenshot-00005.png" caption="" alt="config.json画像2" >}}

以上です。最後まで読んでいただきありがとうございました。

- 関連語句：行端、先頭
