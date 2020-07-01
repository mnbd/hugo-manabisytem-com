---
title: "VSCodeで単語数、文字数、行数、パラグラフ数、読了時間を方法"
date: 2020-07-01T13:14:56+09:00
summary: "VSCodeで単語数、文字数、行数、パラグラフ数、読了時間を知る拡張機能「WordCounter」の使い方をご紹介いたします。"
categories: ["Visual Studio Code（ビジュアルスタジオコード）の使い方"]
tags: ["拡張機能"]
url: "/how-to-use-wordcounter-for-visual-studio-code"
draft: false
---

動作検証バージョン：Windows 10 Home（64bit、バージョン:1909、OSビルド:18363.900）＋Visual Studio Code（バージョン：1.46.1）＋WordCounter（バージョン：2.3.0）

{{< img src="2020-07-01-screenshot-00002.png" caption="" alt="WordCounterロゴ画像" >}}

Visual Studio Code（以下、VSCode）で、拡張機能「WordCounter」をインストールします。

## WordCounter の特徴

- 単語数、文字数、行数、パラグラフ数、およその読了時間（何分で読めるか）を表示する
{{< img src="2020-07-01-screenshot-00008.png" caption="" alt="バーの表示画面" >}}
- 単語数は空白によってカウントされるため、日本語は正しくカウントされない
- 画面下部のバーにリアルタイムで表示する
- 選択範囲がある場合は、その範囲を表示する

## カウント方法

単語数は、文字を空白で区切ってカウントします。全角空白でも半角空白でも区切られます。

文字数は、半角でも全角でも1文字とカウントします。

行数は、空行も1行とカウントします。

パラグラフは、空行で区切ってカウントします。

## インストール方法

1. ブラウザで WordCounter のサイト（{{< exlink href="https://marketplace.visualstudio.com/items?itemName=kirozen.wordcounter" text="https://marketplace.visualstudio.com/items?itemName=kirozen.wordcounter" >}})を開いて、［Install］ボタンを押してください。
{{< img src="2020-07-01-screenshot-00003.png" caption="" alt="" >}}

2. 「Visual Studio Code is required to install this extension」や「Visual Studio Code を開きますか？」というウィンドウが表示された場合は、それぞれ指示に従ってください。
{{< img src="2020-07-01-screenshot-00004.png" caption="" alt="Chrome の画面1" >}}
{{< img src="2020-07-01-screenshot-00005.png" caption="" alt="Chrome の画面2" >}}


3. VSCode が起動して、WordCounter の画面が開いたら、［インストール］をクリックしてください。表示が［アンインストール］に変わったら完了です。
{{< img src="2020-07-01-screenshot-00006.png" caption="" alt="インストール画面" >}}

以上です。最後まで読んでいただきありがとうございました。
