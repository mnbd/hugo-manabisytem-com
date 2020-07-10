---
title: "Windows 10 Home Editionで「ローカルグループポリシーエディター」を起動する方法"
date: 2020-07-10T15:43:46+09:00
summary: "Windows 10 Home Editionで「ローカルグループポリシーエディター」を起動する方法をご紹介いたします。"
categories: [""]
tags: ["Windows（ウィンドウズ）の使い方", "Windows 10（ウィンドウズテン）"]
url: "/how-to-launch-group-policy-enabler-for-windows-10"
draft: false
---

- 動作検証バージョン：Windows 10 Home（64bit、バージョン：1909、OSビルド：18363.900）

Windows 10 Home Editionで「ローカルグループポリシーエディター」を起動する方法をご紹介いたします。

## ローカルグループポリシーエディターとは

Windows 10のシステムに関するさまざまな設定をできるソフトウェアです。

## Windows 10 Home Editionでは起動できない

{{< img src="2020-07-10-screenshot-00006.png" caption="" alt="gbedit.mscを起動した際のウィンドウ画面" >}}

Windows 10 Proでは標準で起動できますが、Windows 10 Home Editionでは特定の設定をしなければ起動できません。

## Windows 10 Homeで起動する方法

1. ブラウザで{{< exlink href="https://www.itechtics.com/easily-enable-group-policy-editor-gpedit-msc-in-windows-10-home-edition/" text="Group Policy Editor" >}}にアクセスして、［GPEdit Enabler for Windows 10 Home Edition］をクリックしてファイルをダウンロードしてください。
{{< img src="2020-07-10-screenshot-00007.png" caption="" alt="ウェブサイト画面" >}}

2. 「gpedit-enabler.bat」というファイルがダウンロードされますので、マウスで右クリックして［管理者として実行］を選択してください。  
{{< img src="2020-07-10-screenshot-00008.png" caption="" alt="右クリックメニュー画面" >}}

3. 黒い画面が開き、設定が始まります。「続行するには何かキーを押してください」というメッセージが表示されたらキーを押します。
{{< img src="2020-07-10-screenshot-00009.png" caption="" alt="コマンドプロンプト画面" >}}

4. ［Windowsロゴ］キー＋［R］キーを押して、［ファイル名を選択して実行］ウィンドウを開き、「gpedit.msc」と入力して［OK］ボタンを押してください。  
{{< img src="2020-07-10-screenshot-00010.png" caption="" alt="ファイル名を選択して実行ウィンドウ画面" >}}

5. ローカルグループポリシーエディターが起動します。  
{{< img src="2020-07-10-screenshot-00011.png" caption="" alt="グループポリシーエディター画面" >}}

## ローカルグループポリシーエディターのファイルの場所

ローカルグループポリシーエディターがインストールされた場所は以下にです。

        C:\Windows\System32\gpedit.msc

以上です。最後まで読んでいただきありがとうございました。

- 関連語句：ホーム
