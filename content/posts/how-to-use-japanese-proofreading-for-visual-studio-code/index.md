---
title: "Visual Studio Codeで日本語テキストの校正を自動でする方法"
date: 2020-07-01T17:14:11+09:00
summary: "Visual Studio Codeの拡張機能「テキスト校正くん」の使い方をご紹介いたします。"
categories: [""]
tags: ["Visual Studio Code（ビジュアルスタジオコード）の使い方", "拡張機能"]
url: "/how-to-use-japanese-proofreading-for-visual-studio-code"
draft: false
---

動作検証バージョン：Windows 10 Home（64bit、バージョン:1909、OSビルド:18363.900）＋Visual Studio Code（バージョン：1.46.1）＋テキスト校正くん（バージョン：0.2.3）

{{< img src="2020-07-01-screenshot-00009.png" caption="" alt="テキスト校正くんアイコン画像" >}}

Visual Studio Code（以下、VS Code）に、拡張機能「テキスト校正くん」をインストールすることで、テキストファイル、md（マークダウン）ファイル、Re:VIEWファイルの日本語をチェックしてくれます。

文章に問題がある場合、その文章の下に波線を表示し、マウスカーソルをそこに移動するとメニューが開くので、そのメニューから［問題を表示（Alt+F8）］をクリックすると問題の詳細を表示してくれます。

校正チェックはリアルタイムに行われるため、文章を修正すると波線が消えます。

## テキスト校正くんの特徴

### 校正ルール

{{< exlink href="https://marketplace.visualstudio.com/items?itemName=ICS.japanese-proofreading" text="テキスト校正くんの公式サイト" >}}から引用します。

> - 「ですます」調と「である」調の混在
> - ら抜き言葉
> - 二重否定
> - 同じ助詞の連続使用
> - 同じ接続詞の連続使用
> - 逆接の接続助詞「が」の連続使用
> - 全角と半角アルファベットの混在
> - 弱い日本語表現の利用（〜かもしれない）
> - 読点の数（1文に4つまで）
> - ウェブの用語や名称の表記統一（Javascript→JavaScript、Github→GitHub等）
> - 漢字の閉じ方、開き方（下さい→ください、出来る→できる等）

### 校正ルールの変更設定項目

 - 1ドキュメントあたりの校正指摘数
- アルファベットが半角表記
- かっこ類と隣接する文字の間のスペース
- 和文にダッシュ
- 和文にハイフン
- 漢字の閉じ開き
- ら抜き言葉
- 一部の助数詞の表記
- 外来語カタカナ表記
- 丸かっこ
- 技術用語
- 疑問符
- 句点、読点
- 固有名詞
- 誤字
- 算用数字
- 算用数字と漢数字の使い分け
- 重言
- 助詞の連続
- 冗長な表現
- 全角文字どうしの間のスペース
- 全角文字と半角文字の間のスペース
- 読点の数（1つの文で4つ以上使ってないか）
- VS Codeと言語サーバー間のトレース

## 実際の校正例

- 同じ助詞の連続  
{{< img src="2020-07-01-screenshot-00012.png" caption="" alt="助詞の連続エラー表示" >}}
- ひらく漢字（ピンクの線はこちらで引いたものです）  
どのように校正するべきか指示してくれます  
{{< img src="2020-07-01-screenshot-00013.png" caption="" alt="ひらく漢字エラー表示" >}}
- 技術用語（ピンクの線はこちらで引いたものです）  
{{< img src="2020-07-01-screenshot-00014.png" caption="" alt="技術用語エラー表示" >}}

## インストール方法

1. ブラウザでテキスト校正くんのサイト（{{< exlink href="hhttps://marketplace.visualstudio.com/items?itemName=ICS.japanese-proofreading" text="https://marketplace.visualstudio.com/items?itemName=ICS.japanese-proofreading" >}})を開いて、［Install］ボタンを押してください。
{{< img src="2020-07-01-screenshot-00010.png" caption="" alt="" >}}

2. 「Visual Studio Code is required to install this extension」や「Visual Studio Codeを開きますか？」というウィンドウが表示された場合は、それぞれ指示にしたがってください。（以下の画面は、Google Chromeの場合）
{{< img src="2020-07-01-screenshot-00004.png" caption="" alt="Chromeの画面1" >}}
{{< img src="2020-07-01-screenshot-00005.png" caption="" alt="Chromeの画面2" >}}


3. VS Codeが起動して、テキスト校正くんの画面が開いたら、［インストール］をクリックしてください。表示が［アンインストール］に変わったら完了です。
{{< img src="2020-07-01-screenshot-00011.png" caption="" alt="インストール画面" >}}

以上です。最後まで読んでいただきありがとうございました。
