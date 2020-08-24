---
title: "常にアルファベットを大文字で入力する機能をオン/オフにする方法"
date: 2020-08-24T14:15:06+09:00
summary: "Caps Lockキーをオフにする方法とMicrosoft IMEの設定でCaps Lockキーを無効にする方法をご紹介いたします。"
categories: [""]
tags: ["Windows（ウィンドウズ）の使い方", "Windows 10（ウィンドウズテン）"]
url: "/how-to-change-from-capital-letter-to-small-letter"
draft: false
---

{{< img src="/images/software/windows10.png" caption="" alt="Windows 10のアイコン画像" >}}

- 動作検証バージョン：Windows 10 Home（64bit、バージョン：1909、OSビルド：18363.900）

PCのキーボードには「Caps Lock（キャプスロック）」キーがあります。

{{< img src="/images/keyboard/keyboard-capslock.png" caption="" alt="［Caps Lock］キーのキーボード配列画像" >}}

Caps Lcokキーをオンにしてあると、キーボードでアルファベットを入力する時に［Shift］キーを押しながらアルファベットキーを押さなくても大文字で入力できます。

しかし、アルファベットを常に大文字で入力するような機会はあまりありませんし、Windows 10での起動時の認証で「CapsLockキーがオンになっています」と表示されることがあるように、パスワードなどの文字を確認できない場面でこのキーがオンになっているとパスワードそのもののの文字に間違えがなくても大文字になっているために認証エラーが出てしまう原因にもなります。

しかも、オフにする方法が意外と知られていないためにトラブルの原因にもなっています。

ここでは、このCaps Lockキーをオン/オフにする方法をご紹介いたします。

## Caps Lockキーをオン/オフにする

1. ［Shift］＋［CapsLock］キーを押してください。  
{{< img src="/images/keyboard/keyboard-left-shift-capslock.png" caption="" alt="［Shift］＋［Caps Lock］キーのキーボード配列画像" >}}

2. キーボード右上のランプが消灯していれば「オフ」になっており、点灯していれば「オン」になっています。  
{{< img src="/images/keyboard/keyboard-capslock-light.png" caption="" alt="［Caps Lock］キーのランプのキーボード配列画像" >}}

## Caps Lockキーを無効にする（MS-IMEの場合）

1. 画面左下の［スタート］ボタンをクリックして、［歯車］ボタンをクリックしてください。  
{{< img src="2020-08-24-screenshot-00001.png" caption="" alt="［スタート］ボタンのメニュー画像" >}}

2. 「Windowsの設定」ウィンドウから［時刻と言語］をクリックしてください。  
{{< img src="2020-08-24-screenshot-00002.png" caption="" alt="Windowsの設定ウィンドウ画像" >}}

3. 左側のナビゲーションメニューから［言語］をクリックして、「優先する言語」の［日本語］をクリックしてください。  
{{< img src="2020-08-24-screenshot-00003.png" caption="" alt="「優先する言語」の画像" >}}

4. 「日本語」から［オプション］ボタンをクリックしてください。  
{{< img src="2020-08-24-screenshot-00004.png" caption="" alt="「日本語」の「オプション」ボタン画像" >}}

5. 「キーボード」から［Microsoft IME］をクリックして、［オプション］ボタンを押してください。  
{{< img src="2020-08-24-screenshot-00005.png" caption="" alt="「キーボード」の設定画像" >}}

6. 「詳細設定」から［詳細設定を開く］をクリックしてください。  
{{< img src="2020-08-24-screenshot-00006.png" caption="" alt="「詳細設定を開く」画像" >}}

7. ［全般］タブの「編集操作」の「キー設定」が［Microsoft IME］になっていることを確認し、［変更］ボタンを押してください。  
{{< img src="2020-08-24-screenshot-00007.png" caption="" alt="IMEの設定画像" >}}

8. 左端の「*キー」列の［英数］をクリックして、［削除］ボタンをクリックして、「英数を削除しますか？よろしいですか」のウィンドウで［OK］ボタンをクリックして、［OK］ボタンをクリックしてください。  
{{< img src="2020-08-24-screenshot-00008.png" caption="" alt="「キー設定」の画像" >}}  
{{< img src="2020-08-24-screenshot-00011.png" caption="" alt="メッセージ画像" >}}

9. 「編集操作」の「キー設定」が［ユーザー定義］になっていて、［OK］ボタンをクリックしてください。  
{{< img src="2020-08-24-screenshot-00009.png" caption="" alt="［ユーザー定義］の画像" >}}

### Caps Lockキーを元に戻したい場合

- 「編集操作」の「キー設定」でプルダウンメニューから［Microsoft IME］を選択してください。  
{{< img src="2020-08-24-screenshot-00010.png" caption="" alt="「言語編集」画像" >}}

## Caps Lockキーを活用する

Caps Lockキーは、キーボードを使う上で押しやすいポジションにあるキーなので、キーボードショートカットを多用する方の中には、違うキーの役割を割り当てている方々もいらっしゃいます。

たとえば、［Ctrl］キーは少し押しづらいポジションですので、この役割をCaps Lockキーに割り当てるようなことが可能です。

具体的にはAutoHotkeyなどのフリーソフトを使用していくことになります。

以上です。最後まで読んでいただきありがとうございました。

- 関連語句：
