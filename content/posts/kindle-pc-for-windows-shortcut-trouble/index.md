---
title: "Kindle for PC（Windows）がキーボード操作で起動してしまう問題の対処法"
date: 2020-07-09T19:34:19+09:00
summary: "Kindle for PCのショートカット起動を無効にする方法についてご紹介いたします。"
categories: [""]
tags: ["Windows（ウィンドウズ）の使い方", "Windows 10（ウィンドウズテン）"]
url: "/kindle-for-pc-shortcut-trouble"
draft: false
---

{{< img src="2020-07-09-screenshot-00004.png" caption="" alt="Kindole for PCのアイコン画像" >}}

- 動作検証バージョン：Windows 10 Home（64bit、バージョン：1909、OSビルド：18363.900）＋Kindle for PC（バージョン：1.28.057030)

他のソフトウェアでキーボード操作している時に、Kindle for PCが突然起動したり、アップデートを始めたりしたことはありませんか？

これは、Kindle for PCの起動にショートカット（［Ctrl］キー＋［Alt］キー＋［K］キー）が割り当てられているために起こります。

## ショートカットの設定を無効にする

1. ［Windowsロゴ］キー＋［E］キーを押して、エクスプローラーを起動してください。

2. 以下のテキストをコピーしてください。

    C:\Users\＜あなたのユーザー名＞\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Amazon\Amazon Kindle

3. エクスプローラーで［Alt］キー＋［D］キーした場所に貼り付けて、＜あなたのユーザー名＞のところをご自身のユーザー名に変えて［Enter］キーを押してください。  
{{< img src="2020-07-09-screenshot-00001.png" caption="" alt="アドレスバー画像" >}}

4. ［Kindle］のショートカットファイルがありますので、右クリックしてプロパティを表示してください。    
{{< img src="2020-07-09-screenshot-00005.png" caption="" alt="右クリックメニュー" >}}

5. ［ショートカットキー(K):］の項目をクリックして、［Back space］キーを押して、［なし］と表示されているのを確認してから［OK］ボタンを押してください。  
{{< img src="2020-07-09-screenshot-00002.png" caption="" alt="プロパティ画像1" >}}
{{< img src="2020-07-09-screenshot-00003.png" caption="" alt="プロパティ画像2" >}}

以上です。最後まで読んでいただきありがとうございました。

- 関連語句：キンドル
