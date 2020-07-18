---
title: "Windowsセキュリティのメモリーの大量消費を軽減する方法"
date: 2020-07-18T14:32:12+09:00
summary: "Antimalware Service Executableによって起こるメモリーの大量消費を軽減する方法"
categories: [""]
tags: ["Windows（ウィンドウズ）の使い方", "Windows 10（ウィンドウズテン）"]
url: "/windows-defender-antivirus-service-memory-trouble"
draft: false
---

{{< img src="2020-07-18-screenshot-00008.png" caption="" alt="Windowsセキュリティ画面画像" >}}

- 動作検証バージョン：Windows 10 Home（64bit、バージョン：1909、OSビルド：18363.900）

Windows 10の動作が異常に遅いとき、Windowsセキュリティの機能に原因のある場合があります。

ここではそのWindowsセキュリティによって起こるメモリーの大量消費を軽減する方法をご紹介いたします。

{{< attention title="" text="ここでご紹介する方法は、PCの動作を改善するためにWindowsセキュリティの機能を弱めることになりますので、操作は自己責任でお願いいたします。" >}}

## Antimalware Service Executableとは

Antimalware Service Executableは、Windowsセキュリティの機能の1つで、悪意のあるプログラムがないかどうかを常時監視しています。

PCの使用環境によってメモリーの使用量がかなり異なります。

100MB前後の方もいれば、1Gを超えてしまう方もいます。

また、一部ユーザーから不具合も報告されており、本来の機能上の増加なのか、プログラムによる不具合なのかはわかりません。CPU使用率の止まらない方もいらっしゃるようです。

しかし、Windowsにおいてセキュリティ対策は必須であり、他社のウィルス対策ソフトを導入していないのであれば、安易に動作を無効化するべきではないでしょう。

## メモリー使用量を確認する

1. ［Ctrl］＋［Alt］＋［Delete］キーを押して、［タスクマネージャー］をクリックしてください。

2. ［プロセス］タブであることを確認し、「Antimalware Service Executable」という項目のメモリ使用量が「1,104.4MB（約1.1ギガ）」とあります。
{{< img src="2020-07-18-screenshot-00001.png" caption="" alt="タスクマネージャー画面" >}}

## Antimalware Service Executableの設定を変更する

「Antimalware Service Executable」はWindows 10起動時に実行されますが、この設定を変更することでメモリー使用量を抑えられます。

1. ［Windowsロゴ］＋［R］キーを押して、［ファイル名を指定して実行］ウィンドウを開き、「taskschd.msc」と入力し［OK］ボタンを押してください。  タスクスケジューラーが起動します。
{{< img src="2020-07-18-screenshot-00002.png" caption="" alt="taskschd.msc実行画面" >}}  
{{< img src="2020-07-18-screenshot-00003.png" caption="" alt="タスクスケジューラー画面" >}}

2. 左側のフォルダー［タイムスケジューラライブラリ］－［Microsoft］－［Windows］－［Windows Defender］をクリックしてください。  
{{< img src="2020-07-18-screenshot-00005.png" caption="" alt="Windows Defenderフォルダー画面" >}}

3. 中央の項目から［Windows Defender Scheduled Scan］をダブルクリックしてください。  
{{< img src="2020-07-18-screenshot-00006.png" caption="" alt="Windows Defender Scheduled Scan項目画面" >}}

4. 開いた［Windows Defender Scheduled Scanのプロパティ］ウィンドウで、［最上位の特権で実行する］をチェックを外してください。  
{{< img src="2020-07-18-screenshot-00007.png" caption="" alt="Windows Defender Scheduled Scanのプロパティ画面" >}}

5. しばらくするとメモリー使用量が「312.6MB」にまで減りました。  PCの使用環境によって増減に幅があります。  
{{< img src="2020-07-18-screenshot-00009.png" caption="" alt="タスクマネージャー画面" >}}

以上です。最後まで読んでいただきありがとうございました。

- 関連語句：重い、止まらない
