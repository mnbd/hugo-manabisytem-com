---
title: "AutoHotkeyを使用して定型文を挿入する方法"
date: 2020-06-10T12:51:18+09:00
summary: "フリーソフトのプログラム言語「AutoHotkey」を使用して、定型文を挿入する方法をご紹介いたします。"
categories: ["サービス／ソフト"]
tags: ["AutoHotkey","Windows"]
url: "/text-expansion-using-autohotkey"
draft: false
---

{{< img src="2020-06-10-screenshot-00001.png" caption="" alt="AutoHotkeyロゴ画像" >}}

フリーソフトのプログラム言語「AutoHotkey」を使用して、定型文を挿入する方法をご紹介いたします。

AutoHotkeyはWindowsでのみ動作します。

- {{< exlink href="https://www.autohotkey.com/" text="AutoHotkeyオフィシャルサイト" >}}

## 動作

このような動作が可能です。文字入力の効率化に役立ちます。

以下の例では、「;hello」と入力すると同時に定型文に置き換わります。

{{< gif src="autohotkey-hotstring.gif" caption="" alt="定型文の挿入の事例" >}}

## 設定の手順

### AutoHotkeyファイルの作成

以下の内容のファイルを「AutoHotkeyU64.ahk」としてAutoHotkeyのインストールフォルダに作成します。

AutoHotkeyU64.ahk
```html
#Hotstring *
#Hotstring O

::;hello::
Send, こんにちは。まなびシステムです。`n記事を読んでいただいてありがとうございます。
Return
```

### AutoHokeyファイルの起動

AutoHotkeyのインストールフォルダにある「AutoHotkey.exe」を起動します。

以下のように右下のタスクトレイに画像が表示されていれば起動しています。

ahkファイルの内容を変更した場合は、変更内容を反映させるためにタスクバーのロゴを右クリックして「Reload This Script」を選択してください。

{{< img src="2020-06-10-screenshot-00002.png" caption="" alt="Autohotkeyのタスクバーのロゴ画像" >}}

## AutoHotkeyファイルの書き方

### 基礎編

（定型文に置き換えるための文字）に置き換える引き金となる文字を英数文字で記入してください。

```html
#Hotstring *
#Hotstring O

::（定型文に置き換えるための文字）::
Send, （挿入したい定型文）
Return

::（定型文に置き換えるための文字）::
Send, （挿入したい定型文）
Return

::（定型文に置き換えるための文字）::
Send, （挿入したい定型文）
Return
```

### 応用編

#### 複数行にわたる定型文を挿入したい場合

「`n」を記入することで改行させることができます。

```html
#Hotstring *
#Hotstring O

::（定型文に置き換えるための文字）::
Send, （1行目挿入したい定型文）`n（2行目に挿入したい文字）`n
Return
```

### 挿入した定型文の途中にカーソルを置きたい場合

定型文の途中にカーソルを置くことで方向キーで移動することなくすぐに文字入力が可能になります。

定型文の最後に「{Left 数字}」を記入します。

以下の例では、定型文の最後の文字をカーソルの出発点として2文字戻ることを意味しています。

数字は英数字でも日本語でもそれぞれ1文字は1とカウントします。

```html
#Hotstring *
#Hotstring O

::（定型文に置き換えるための文字）::
Send, （挿入したい定型文）{Left 2}
Return
```

### 挿入する定型文の中にクリップボードの内容を貼り付ける場合

挿入したい定型文の特定の場所に現在のクリップボードの内容を貼り付けることが可能です。

「%clipboard%」と記入した場所にその内容が貼り付けられます。

```html
#Hotstring *
#Hotstring O

::（定型文に置き換えるための文字）::
Send, （挿入したい定型文）%clipboard%（挿入したい定型文）
Return
```

### 今日の日付を挿入する場合

以下を記入することで今日の日付を挿入することができます。

「;today」と入力すると「2020/06/10」の書式で置き換わります。 

```html
#Hotstring *
#Hotstring O

::;today::
FormatTime, TimeString,, yyyy/MM/dd
Send, %TimeString%{Space}
Return
```

## 使用上の注意点

### 日本語IMEによる誤動作

AutoHotkeyを起動していると日本語IMEがオンでも定型文の挿入が作動してしまいます。文字化けや意図した文字に置き換わらないなどします。

### 定型文で使用する文字制限

AutoHotkeyはプログラム言語なので、プログラムを記述するための文字を定型文に使用すると意図した動作にならない場合があります。その場合はahkファイルの「Send」の部分を「Sendraw」に書き換えてみてください。

## 似た機能を持つソフトウェア

### Phrase Express

AutoHotkeyと違い、ウィンドウ画面の中で設定や定型文の管理が可能です。

ソフトウェアが英語で商用利用は有料です。

- {{< exlink href="https://www.phraseexpress.com/" text="Phrase Expressオフィシャルサイト" >}}

### Clipboard History

クリップボードの機能を拡張するフリーソフトです。

- {{< exlink hrnef="https://blank-note.sakura.ne.jp/" text="Clipboard Historyオフィシャルサイト" >}}

### Clibor

クリップボードの機能を拡張するフリーソフトです。

- {{< exlink href="https://chigusa-web.com/" text="Cliborオフィシャルサイト" >}}

以上です。読んでいただきありがとうございました。
