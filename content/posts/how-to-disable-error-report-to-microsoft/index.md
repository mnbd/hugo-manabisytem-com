---
title: "アプリやソフトのエラー情報をMicrosoftに送信しない方法"
date: 2020-07-21T13:16:24+09:00
summary: "ローカルグループポリシーエディターを使ってアプリやソフトウェアのエラー情報をMicrosoftに送信しないようにする方法をご紹介いたします。"
categories: [""]
tags: ["Windows（ウィンドウズ）の使い方", "Windows 10（ウィンドウズテン）"]
url: "/how-to-disable-error-report-to-microsoft"
draft: false
---

{{< img src="/images/software/windows10.png" caption="" alt="Windowsのアイコン画像" >}}

- 動作検証バージョン：Windows 10 Home（64bit、バージョン：1909、OSビルド：18363.900）

アプリやソフトが突然応答しなくなったり、終了したりして「Windowsの問題をMicrosoftに報告しています。」というメッセージが表示されたことはありませんか？

何が送信されているのかわからず、このようなメッセージに不安を抱かれる方もいらっしゃるかと思います。

ここでは、これらのエラー情報を送信しない方法をご紹介いたします。

## ローカルグループポリシーエディター

この設定にはローカルグループポリシーエディターが必要です。

お使いのWindows 10がPro Editionの場合は以下の手順にお進みください。

Home Editionの場合は、{{< exlink href="https://manabisystem.com/how-to-launch-group-policy-enabler-for-windows-10/" text="Windows 10 Home Editionで「ローカルグループポリシーエディター」を起動する方法" >}}をご覧になって設定してください。

## エラー報告を無効にする手順

1. ［Windowsロゴ］＋［R］キーで［ファイル名を指定して実行］ウィンドウを開いてください。入力フォームに「gpedit.msc」と入力して［OK］ボタンを押してください。  
{{< img src="2020-07-21-screenshot-00001.png" caption="" alt="ファイル名を指定して実行" >}}

2. ローカルグループポリシーエディターが起動します。  
{{< img src="2020-07-21-screenshot-00002.png" caption="" alt="ローカルグループポリシーエディター画面" >}}

3. 画面左側の階層フォルダーから［コンピューターの構成］－［管理者用テンプレート］－［Windowsコンポーネント］－［Windowsエラー報告］をクリックして、画面右側の［Windowsエラー報告を無効にする］をダブルクリックしてください。（ご自身のユーザーアカウントだけ無効にしたい場合は、［コンピューターの構成］ではなく、［ユーザーの構成］をクリックしてください）  
{{< img src="2020-07-21-screenshot-00003.png" caption="" alt="Windowsエラー報告フィルダーの表示画面" >}}

4. 左上ボタンから［有効］をクリックして、右下の［OK］ボタンを押してください。  
{{< img src="2020-07-21-screenshot-00004.png" caption="" alt="［Windowsエラー報告を無効にする画面" >}}

以上です。最後まで読んでいただきありがとうございました。

- 関連語句：マイクロソフト、レポート、ソフトウェア、アプリケーション
