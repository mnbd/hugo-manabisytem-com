---
title: "Mozilla FirefoxでPocketにキーボードショートカットを使ってページを保存する方法"
date: 2020-07-13T11:11:52+09:00
summary: "Firefox（ファイヤーフォックス）でPocket（ポケット）にキーボードから保存する方法をご紹介いたします。"
categories: [""]
tags: ["サービス/ソフトの使い方"]
url: "/how-to-save-pages-on-pocket-using-keyboard-shortcut-for-firefox"
draft: false
---

{{< img src="/images/software/firefox.png" caption="" alt="Firefoxのアイコン画像" >}}

- 動作検証バージョン：Windows 10 Home（64bit、バージョン：1909、OSビルド：18363.900）＋Firefox Browser（バージョン：78.0.2）

Mozilla Firefox（ファイヤーフォックス）には、Pocket（ポケット）というオンラインブックマークサービスを使うための機能が組み込まれています。

しかしキーボードのショートカット（キーボード入力だけでブックマークする）がありません。

この記事では、ブックマークレットという機能と拡張機能の「ShortcutKey2URL」を利用して、キーボードショートカットを実現する方法をご紹介いたします。

## ShortcutKey2URLのインストール

1. Firefoxで「ShortcutKey2URL for Firefox WebExtensions」（{{< exlink href="https://addons.mozilla.org/ja/firefox/addon/shortcutkey2url/" text="https://addons.mozilla.org/ja/firefox/addon/shortcutkey2url/" >}}）にアクセスして、［追加］ボタンをクリックしてください。  
{{< img src="2020-07-13-screenshot-00001.png" caption="" alt="ShortcutKey2URLのページ画面" >}}

2. ［ShortcutKey2URL（WebExtensions）を追加しますか？］というウィンドウが開きますので［追加］をクリックしてください。  
{{< img src="2020-07-13-screenshot-00002.png" caption="" alt="ShortcutKey2URL（WebExtensions）を追加しますか？画面" >}}

3. ［ShortcutKey2URL（WebExtensions）がFirefoxに追加されました。］というウィンドウが開きますので［OK］をクリックしてください。  インストールは完了です。
{{< img src="2020-07-13-screenshot-00003.png" caption="" alt="ShortcutKey2URL（WebExtensions）がFirefoxに追加されました。画面" >}}  
{{< img src="2020-07-13-screenshot-00004.png" caption="" alt="ShortcutKey2URLのアイコン画像" >}}

## Pocketのブックマークレットを取得

1. PocketのFirefox用のブックマークレット（{{< exlink href="https://getpocket.com/add?sb=1" text="https://getpocket.com/add?sb=1" >}}）のページにアクセスしてください。

2. ［+ Pocket］をマウスで右クリックして［リンクのURLをコピー］を選択してください。  
{{< img src="2020-07-13-screenshot-00005.png" caption="" alt="右クリックメニュー画面" >}}

## ShortcutKey2URLの設定

1. 右上のShortcutKey2URLのアイコンをクリックしてください。  
{{< img src="2020-07-13-screenshot-00004.png" caption="" alt="ShortcutKey2URLのアイコン画像" >}}

2. 開いた画面から［Options］をクリックしてください。  
{{< img src="2020-07-13-screenshot-00007.png" caption="" alt="起動画面" >}}

3. 設定画面が開きますので、それぞれの項目に文字を入力してください。［Script］には先ほどPocketでコピーした内容を貼り付けてください。最後に［Save］ボタンをクリックしてください。  
{{< img src="2020-07-13-screenshot-00010.png" caption="" alt="設定例画面" >}}

{{< table class="table table-hover table-condensed " >}}

名前|説明
---|---
Key|動作を発動するキー
Action|動作の選択
Title|メニューに表示される文字
URL|動作に必要なアドレス
Script|動作に必要なスクリプト

{{</ table >}}

## Pocketに保存する

1. ［Ctrl］＋［.（ピリオド）］キーを押すと右上にショートカットメニューが開きます。  
{{< img src="2020-07-13-screenshot-00011.png" caption="" alt="ショートカットメニュー画面" >}}

2. ［P］キーを押すとページ画面の上部にメッセージが表示されます。  
{{< img src="2020-07-13-screenshot-00012.png" caption="" alt="Pocket Savedメッセージ画面" >}}

以上です。最後まで読んでいただきありがとうございました。

- 関連語句：ポケット、ファイヤーフォックス、モジラ
