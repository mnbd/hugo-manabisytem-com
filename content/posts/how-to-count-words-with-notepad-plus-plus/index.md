---
title: "テキストエディタ「Notepad++」で文字数をカウントする方法"
date: 2020-06-08T22:26:11+09:00
summary: "テキストエディタ「Notepad++」で文字数をカウントする方法をご紹介いたします。"
categories: [""]
tags: ["サービス/ソフトの使い方"]
draft: false
url: "/how-to-count-words-with-notepad-plus-plus"
---

{{< img src="2020-06-08-screenshot-00005.png" alt="Notepad++のロゴ画像" >}}

テキストエディタ「Notepad++」で文字数をカウントする方法をご紹介いたします。

{{< exlink href="https://notepad-plus-plus.org/" text="Notepad++" >}}

機能は同じですが、やり方が2通りあります。

## 方法1. ウィンドウの特定の箇所をマウスでダブルクリック

{{< img src="2020-06-08-screenshot-00001.png" alt="ステータスバーの画像">}}

## 方法2. メニューの「表示」→「概要...」

{{< img src="2020-06-08-screenshot-00002.png" alt="表示メニューの画像" >}}

{{< img src="2020-06-08-screenshot-00003.png" alt="表示メニューの画像" >}}

## 概要ウィンドウ

{{< img src="2020-06-08-screenshot-00004.png" alt="概要ウィンドウの画像" >}}

### 文字数

英数字と日本語ともに1文字としてカウントします。

### 語数

半角の空白を区切りとしてカウントされます。

全角の空白は区切りとはカウントされません。

#### 半角と全角を混じえた文字数カウントの例

{{< table class="table table-hover table-condensed " >}}
|文字|カウント数|
|---|---|
|this is a pen|4語|
|これはペンです| 1語 |
|これは　ペンです| 1語 |
|これは ペンです| 2語 |
{{</ table >}}

## その他

行数や選択範囲の文字数のカウントもできます。

以上です。読んでいただきありがとうございました。
