---
title: "PC の使用履歴を記録して統計を取る方法"
date: 2020-06-22T13:44:15+09:00
summary: "PC の使用履歴を記録して集計し、グラフ表示してくれるソフトウェアの使い方をご紹介いたします"
categories: [""]
tags: ["サービス/ソフトの使い方"]
url: "/how-to-use-manic-time"
draft: false
---

{{< img src="2020-06-22-screenshot-00001.png" caption="" alt="ManicTime ロゴ画像" >}}

## ManicTime

PC の使用履歴を記録して集計し、グラフ表示してくれるソフトウェアです。

- 動作環境
  - Windows
    - Windows 10, Windows 8.1 and Windows 7
  - Mac
  - Linux
  - Android
- ウェブサイト
  - {{< exlink href="https://manictime.com/" text="ManicTime" >}}

ここでは Windows の USB ポータブルバージョンを例にインストールから使い方をご紹介いたします。

- {{< exlink href="https://manabisystem.com/term-usb-portable/" text="USB Portable（USBポータブル） とは" >}}

## インストール

{{< exlink href="https://manictime.com/" text="ManicTime" >}}にブラウザでアクセスしてください。そして「More download options」をクリックしてください。

{{< img src="2020-06-22-screenshot-00003.png" caption="" alt="ウェブサイト" >}}

ダウンロードページで「Portable version(usb)」をクリックしてください。

{{< img src="2020-06-22-screenshot-00004.png" caption="" alt="ダウンロード" >}}

ダウンロードした「ManicTimeUsb.zip」を任意の場所に解凍してください。

{{< img src="2020-06-22-screenshot-00008.png" caption="" alt="フォルダの中身" >}}

「ManicTime Client.exe」をダブルクリックしてください。ライセンスの選択をしますが、ここでは「スタンダード（無料）」を選択して、「OK」ボタンを押します。

{{< img src="2020-06-22-screenshot-00005.png" caption="" alt="ライセンス" >}}

スタンダード（無料）では以下の機能が無効になります。

{{< img src="2020-06-22-screenshot-00006.png" caption="" alt="スタンダードで無効になる機能" >}}

## 使い方

ManicTime で使用履歴を記録する場合、常に「ManicTime Client.exe」を起動しておかなければなりません。通常では、最小化表示にすると、タスクトレイにアイコンが表示されます。基本的な操作はこれだけで、後は使用履歴が蓄積されて統計を表示してくれます。

{{< img src="2020-06-22-screenshot-00007.png" caption="" alt="起動画面" >}}

### 「日」タブ

#### 中央グラフ

{{< img src="2020-06-22-screenshot-00009.png" caption="" alt="中央グラフ" >}}

##### コンピューターの使用量

コンピューターの使用量では、コンピューターが利用されていた時間帯をグリーン、起動はされているが利用されていない時間帯をレッド、起動していない時間帯はホワイト（空白）で表示します。

##### アプリケーション

アプリケーションでは、その時間帯に使用していたアプリケーションが色分けされて表示されます。マウスカーソルを置くことでどんなアプリケーションを何時から何時まで使用していたかがわかります。

##### ドキュメント

ドキュメントでは、どのウェブサイトにアクセスしていたかなどの情報が色分けされて表示されます。

#### アプリケーション利用履歴

使用したアプリケーションをリアルタイムで表示します。

{{< img src="2020-06-22-screenshot-00010.png" caption="" alt="アプリケーション利用履歴" >}}

#### アプリケーション利用率

利用率の高いアプリケーション順に表示します。

{{< img src="2020-06-22-screenshot-00011.png" caption="" alt="アプリケーション利用率" >}}

### 「統計」タブ

日付で指定した範囲の統計を表示します。

#### 1日の継続利用時間

1日の継続した利用時間を棒グラフで表示します。

{{< img src="2020-06-22-screenshot-00012.png" caption="" alt="1日の継続利用時間" >}}

#### トップアプリケーション

アプリケーションの合計利用時間を表示します。

{{< img src="2020-06-22-screenshot-00013.png" caption="" alt="トップアプリケーション" >}}

#### トップドキュメント

アクセスしたサイトの合計時間を表示します。

{{< img src="2020-06-22-screenshot-00014.png" caption="" alt="トップドキュメント" >}}

#### トップコンピューターの使用量

コンピューターの使用量を表示します。

{{< img src="2020-06-22-screenshot-00015.png" caption="" alt="トップコンピューターの使用量" >}}

### 設定

ManicTime の起動の設定や表示テーマの設定、ログのバックアップの設定などができます。

{{< img src="2020-06-22-screenshot-00016.png" caption="" alt="設定" >}}

「追跡」では、どのように使用履歴を記録するかを設定できます。

{{< img src="2020-06-22-screenshot-00017.png" caption="" alt="追跡" >}}

### ログ容量の目安

実際の蓄積されるデータ（ログ）ファイルは、約1ヶ月間平均 PC 稼働12時間で、約110MBになります。データファイルは ManicTime フォルダの Data フォルダに蓄積されます。

{{< img src="2020-06-22-screenshot-00018.png" caption="" alt="Data フォルダ" >}}

### メモリ使用量

Windows 10 Home でのメモリ使用量は、61MB です。

{{< img src="2020-06-22-screenshot-00019.png" caption="" alt="メモリ使用量" >}}

以上です。読んでいただきありがとうございました。
