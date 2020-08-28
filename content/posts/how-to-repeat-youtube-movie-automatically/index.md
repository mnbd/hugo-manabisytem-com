---
title: "再生リストを作らずにYouTube動画を繰り返し再生する方法"
date: 2020-08-28T16:54:18+09:00
summary: "YouTubeの動画を簡単に繰り返し再生する方法をご紹介いたします。"
categories: [""]
tags: ["サービス/ソフトの使い方"]
url: "/how-to-repeat-youtube-movie-automatically"
draft: false
---

{{< img src="2020-08-28-screenshot-00003.png" caption="" alt="Listen on Reapeatサイトロゴ画像" >}}

- 動作検証バージョン：Windows 10 Home（64bit、バージョン：1909、OSビルド：18363.900）＋Firefox Browser（バージョン：79.0）

YouTube動画をBGM代わりにしている場合、同じ動画を繰り返し再生したいと思ったことはありませんか？

YouTubeで1つの動画の再生リストを作って繰り返すこともできますが、そこまでしなくてもいいということもあるのではないでしょうか。

ここでは、YouTube動画を簡単に繰り返し再生するためのサイトをご紹介いたします。

## Listen On Repeat

Listen On Repeat（{{< exlink href="https://www.listenonrepeat.com" text="https://www.listenonrepeat.com" >}}）は、YouTube動画を繰り返し再生してくれるサイトです。

## 使い方

1. 繰り返し再生したいYouTube動画にアクセスしてください（例：{{< exlink href="https://www.youtube.com/watch?v=7Kb8V7G66Bk" text="超集中できる自然音。" >}}）
{{< img src="2020-08-28-screenshot-00002.png" caption="" alt="Listen On Repeatのウェブサイト" >}}

2. ブラウザのアドレスに「repeat」を追加してください。  
{{< img src="2020-08-28-screenshot-00005.png" caption="" alt="URL画像" >}}

3. ［Enter］キーを押すとListen On Repeatのサイトに接続されYouTube動画が表示されますので、画面右上の［▶］ボタンをクリックしてください。  
{{< img src="2020-08-28-screenshot-00007.png" caption="" alt="再生ボタン画像" >}}

## ブックマークレット

ブックマークレットを使うことで、「repeat」という文字を自分で入力する必要がなくなります。

```javascript
javascript: (function () {let d=document;let u=location.href;i=u.match(/[^=]+$/);window.open('https://www.youtuberepeat.com/watch?v='+i, '_blank');})();
```

### ブックマークレットの作成例（Firefoxの場合）

1. ［Ctrl］＋［Shift］＋［B］キーを押して「ブラウジングライブラリ」を表示してください。  
{{< img src="2020-08-28-screenshot-00009.png" caption="" alt="ブラウジングライブラリ画像" >}}

2. ブックマークリストでマウスを右クリックして［新しいブックマーク］をクリックしてください。  
{{< img src="2020-08-28-screenshot-00008.png" caption="" alt="右クリックメニュー画像" >}}

3. 「名前」にはわかりやすい名称、「URL」に上記文字列をコピー＆ペーストしてください  
{{< img src="2020-08-28-screenshot-00006.png" caption="" alt="「新しいブックマーク」ウィンドウ画像" >}}

4. 繰り返したいYouTubeのサイトでこの作成したブックマークをクリックするとListen On Repeatのサイトにつながります。

{{< point title="ブックマークレットとは" text="ブックマークのURL欄に上記のような文字を入力することで機能する簡易プログラムです。" >}}

以上です。最後まで読んでいただきありがとうございました。

- 関連語句：リピート、ウェブサービス
