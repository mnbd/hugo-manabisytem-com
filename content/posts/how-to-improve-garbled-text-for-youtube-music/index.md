---
title: "YouTube Musicにアップロードする音楽ファイルの文字化けを解消する方法"
date: 2020-08-10T13:30:45+09:00
summary: "YouTube Musicにアップロードする音楽ファイルの文字化けを直す方法についてご紹介いたします。"
categories: [""]
tags: ["サービス/ソフトの使い方"]
url: "/how-to-improve-garbled-text-for-youtube-music"
draft: false
---

{{< img src="2020-08-10-screenshot-00002.png" caption="" alt="YouTube Musice画像" >}}

- 動作検証バージョン：Windows 10 Home（64bit、バージョン：1909、OSビルド：18363.900）＋STEP_K（バージョン：1.03e）

YouTube Music（{{< exlink href="https://music.youtube.com/" text="https://music.youtube.com/" >}}）で自分が所有しているmp3ファイルをアップロードできるようになりました。

基本的にはGoogleアカウントにログインした状態でYouTube Musicのページを開き、メニューの「音楽をアップロード」からお手持ちのmp3ファイルを選択します。  
{{< img src="2020-08-10-screenshot-00003.png" caption="" alt="YouTube Musicメニュー画面" >}}

しかしここで注意しなければいけないのは、トラック名が日本語の音楽ファイルですと文字化けする可能性があることです。

現在（2020/08/10）のYouTube Musicでは、トラック名を修正できませんのでそのままになってしまいます。

文字化けの原因は、「ID3タグ」の文字コードにあります。

この文字コードがYouTube Musicに対応していないと文字化けしてしまうので、アップロードする前に変換する必要があります。

ここでは、フリーソフトのタグエディター「STEP_K」を使用して文字コードを変換する方法をご紹介いたします。

{{< attention title="" text="ここで紹介する方法は自己責任でお願いいたします。mp3ファイルに変更を加えるものなので、バックアップを取るなどしてお試しください。" >}}

## STEP_Kのダウンロードとインストール

1. Vector（{{< exlink href="https://www.vector.co.jp/soft/dl/winnt/art/se514010.html" text="https://www.vector.co.jp/soft/dl/winnt/art/se514010.html" >}}）ページをブラウザで開いて「ダウンロードページへ」をクリックしてください。  
{{< img src="2020-08-09-screenshot-00008.png" caption="" alt="ダウンロード画面1" >}}

2. 「今すぐダウンロード」をクリックして、任意の場所へ保存してください。  
{{< img src="2020-08-09-screenshot-00009.png" caption="" alt="ダウンロード画面2" >}}

3. 保存した「STEP_K_103e.exe」をダブルクリックして解凍してください。以下のウィンドウ画面が開いたら［Extract］ボタンをクリックしてください。ｓ  
{{< img src="2020-08-09-screenshot-00010.png" caption="" alt="7zip解凍ウィンドウ画面" >}}

4. 「x64」フォルダーをダブルクリックして「SuperTagEditor.exe」をダブルクリックするとSTEP_Kが起動します。  
{{< img src="2020-08-09-screenshot-00011.png" caption="" alt="解凍したフォルダー" >}}  
{{< img src="2020-08-09-screenshot-00012.png" caption="" alt="x64フォルダー" >}}

## 文字コードを変換する手順

1. STEP_Kを起動したら、左上の左から2番目のアイコンをクリックして文字化けするファイルのあるフォルダーを選択してください。  
{{< img src="2020-08-10-screenshot-00004.png" caption="" alt="STEP_K起動画面ｓ" >}}

2. フォルダー内の音楽ファイルが読み込まれたら、音楽ファイルを選択します。1番の位置でマウスをクリックして表示をグレー反転させて、最下部の位置で［Shift］キーを押しながらマウスをクリックしてください。画像のように全体が青く反転したら成功です。  
{{< img src="2020-08-10-screenshot-00005.png" caption="" alt="選択手順画面" >}}

3. 青く反転した状態でマウスを右クリックしてください。メニューから［ID3v2に変換/バージョン・文字エンコード変換（MP3）］を選択してください。  
{{< img src="2020-08-10-screenshot-00006.png" caption="" alt="右クリックメニュー画面" >}}

4. 「ID3v2に変換/バージョン・文字エンコード変換（MP3）」ウィンドウが表示されますので、バージョンを［v2.3］に、文字エンコードを［UTF-16］にして［はい］ボタンをクリックしてください。  
{{< img src="2020-08-10-screenshot-00007.png" caption="" alt="「ID3v2に変換/バージョン・文字エンコード変換（MP3）」ウィンドウ画面" >}}

以上です。最後まで読んでいただきありがとうございました。

- 関連語句：
