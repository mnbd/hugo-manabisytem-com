---
title: "Visual Studio Code（VSCode）ショートカットキー一覧"
date: 2020-06-30T15:24:53+09:00
summary: "Visual Studio Code（ビジュアルスタジオコード） ショートカットキー一覧です。"
categories: ["サービス／ソフト"]
tags: [""]
url: "/visual-studio-code-shortcut-list"
draft: false
---

## Visual Studio Code（ビジュアルスタジオコード） ショートカットキー一覧

Visual Studio Code（以下、VSCode）のメニュー ［ヘルプ］→［キーボードショートカットの参照］で表示される PDF ファイル（{{< exlink href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf" text="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf" >}}）を翻訳したものです。

「他のキー1」や「他のキー2」は、指定の［Ctrl］キーや［Alt］キーを押しながら、それぞれ順番にキーを押してください。「他のキー2」にカッコがついているものは、指定の［Ctrl］や［Alt］などを離してから、単独で押してください。

例えば、「ファイル管理」の「エクスプローラーでアクティブファイルを表示する」ショートカットの場合、［Ctrl］キー＋［K］キーを押した後に、［Ctrl］キーを離してから［R］キーを押します。

ショートカットキーは、Windows表記になっています。Macでは以下に読み替えてください。
{{< table class="table table-hover table-condensed " >}}

Windows|Mac
---|---
Ctrl|⌘ command
Alt|⌥ option

{{</ table >}}

### 全般

{{< table class="table table-hover table-condensed " >}}

Ctrl|Alt|Shift|他のキー1|他のキー2|機能
---|---|---|---|---|---
Ctrl||Shift|P||コマンドパレットを表示
||||F1|||コマンドパレットを表示
Ctrl|||P||クイックオープン、ファイルに移動…
Ctrl||Shift|N||新しいウィンドウ/インスタンス
Ctrl||Shift|W||ウィンドウ/インスタンスを閉じる
Ctrl|||+||ユーザー設定
Ctrl|||K|S|キーボードショートカット

{{</ table >}}

### 基本的な編集

{{< table class="table table-hover table-condensed " >}}

Ctrl|Alt|Shift|他のキー1|他のキー2|機能
---|---|---|---|---|---
Ctrl|||X||カットライン（空の選択）
Ctrl|||C||行のコピー（空の選択）
||Alt||↑/↓||ラインを上下に移動
||Alt|Shift|↑/↓||行を上/下にコピー
Ctrl||Shift|K||行を削除
Ctrl|||Enter||下に行を挿入
Ctrl||Shift|\\||一致するブラケットにジャンプ
Ctrl|||]/[||インデント/アウトデント行
Ctrl|||Home||ファイルの先頭に移動
Ctrl|||End||ファイルの最後に移動
Ctrl|||↑/↓||行を上下にスクロール
|Alt|||PgUp/PgDn||ページを上下にスクロール
Ctrl||Shift|[||折りたたみ領域
Ctrl||Shift|]||展開領域
Ctrl|||K|[|すべてのサブリージョンを折りたたむ
Ctrl|||K|0|すべてのサブリージョンを展開する
Ctrl|||K|J|すべての領域を折りたたむ
Ctrl|||K|C|行コメントを追加
Ctrl|||K|U|行コメントを削除
Ctrl|||/||行コメントを切り替え
||Alt|Shift|A||ブロックコメントの切り替え
||Alt||Z||ワードラップを切り替え

{{</ table >}}

### ナビゲーション

{{< table class="table table-hover table-condensed " >}}

Ctrl|Alt|Shift|他のキー1|他のキー2|機能
---|---|---|---|---|---
Ctrl|||T||全てのシンボルを表示
Ctrl|||G||行に移動...
Ctrl|||P||ファイルに移動...
Ctrl||Shift|O||シンボルに移動...
Ctrl||Shift|M||問題パネルを表示
||||F8||次のエラーまたは警告に進む
Ctrl||Shift|Tab||エディターグループの履歴を移動する
||Alt||←/→||戻る/進む
Ctrl|||M||タブを切り替えてフォーカスを移動

{{</ table >}}

### 検索と置換

{{< table class="table table-hover table-condensed " >}}

Ctrl|Alt|Shift|他のキー1|他のキー2|機能
---|---|---|---|---|---
Ctrl|||F||探す
Ctrl|||H||交換する
||||F3||次/前を見つける
|||Shift|F3||次/前を見つける
|Alt|||Enter||一致するものをすべて選択
Ctrl|||D||次の一致を検索に選択を追加
Ctrl|||K|D|最後の選択を次の一致に移動
||Alt||C||大文字と小文字を区別する
||Alt||R||正規表現
||Alt||W||単語全体を切り替える

{{</ table >}}

### マルチカーソルと選択

{{< table class="table table-hover table-condensed " >}}

Ctrl|Alt|Shift|他のキー1|他のキー2|機能
---|---|---|---|---|---
||Alt||マウスクリック||カーソル挿入
Ctrl|Alt||↑/↓||上/下にカーソルを挿入
Ctrl|||U||最後のカーソル操作を元に戻す
||Alt|Shift|I||選択した各行の終わりにカーソルを挿入します
Ctrl|||L||現在の行を選択
Ctrl||Shift|L||現在の選択のすべての出現を選択
Ctrl|||F2||現在の単語のすべての出現箇所を選択
||Alt|Shift|→||選択の拡大
||Alt|Shift|←||選択を縮小
||Alt|Shift|マウスドラッグ||列（ボックス）の選択
Ctrl|Alt|Shift|↑/↓/←/→||列（ボックス）の選択
Ctrl|Alt|Shift|PgUp/PgDn||列（ボックス）選択ページの上下

{{</ table >}}

### 言語編集

{{< table class="table table-hover table-condensed " >}}

Ctrl|Alt|Shift|他のキー1|他のキー2|機能
---|---|---|---|---|---
Ctrl|||Space||トリガーの提案
Ctrl||Shift|Space||トリガーパラメーターのヒント
||Alt|Shift|F||ドキュメントのフォーマット
Ctrl|||K|F|フォーマットの選択
||||F12|||定義に移動
Ctrl|||K|F12|側面の定義を開く
Ctrl|||.||クイックフィックス
|||Shift|F12||参照を表示
||||F2||シンボルの名前を変更
Ctrl|||K|X|末尾の空白を削除する
Ctrl|||K|M|ファイルの言語を変更する

{{</ table >}}

### エディター管理

{{< table class="table table-hover table-condensed " >}}

Ctrl|Alt|Shift|他のキー1|他のキー2|機能
---|---|---|---|---|---
Ctrl|||F4||エディターを閉じる
Ctrl|||W||エディターを閉じる
Ctrl|||KF||フォルダを閉じる
Ctrl|||\\||分割エディター
Ctrl|||１/2/3||1/2/3番グループへフォーカス
Ctrl|||K|←/→|前/次のエディターグループにフォーカス
Ctrl||Shift|PgUp/PGDn||エディターを左/右に移動
Ctrl|||K|←/→|アクティブな編集グループを移動

{{</ table >}}

### ファイル管理

{{< table class="table table-hover table-condensed " >}}

Ctrl|Alt|Shift|他のキー1|他のキー2|機能
---|---|---|---|---|---
Ctrl|||N||新しいファイル
Ctrl|||O||ファイルを開く...
Ctrl|||S||保存する
Ctrl||Shift|S||名前を付けて保存...
Ctrl|||K|(S)|全部を保存
Ctrl|||F4||閉じる
Ctrl|||K|W|すべて閉じる
Ctrl||Shift|T||閉じたエディタを再度開く
Ctrl|||K|Enter|プレビューモードエディターを開いたままにする
Ctrl|||Tab||次を開く
Ctrl||Shift|Tab||前を開く
Ctrl|||K|(P)|アクティブファイルのパスをコピー
Ctrl|||K|(R)|エクスプローラーでアクティブファイルを表示する
Ctrl|||K|(O)|アクティブなファイルを新しいウィンドウ/インスタンスに表示

{{</ table >}}

### 表示

{{< table class="table table-hover table-condensed " >}}

Ctrl|Alt|Shift|他のキー1|他のキー2|機能
---|---|---|---|---|---
||||F11||フルスクリーン切り替え
||Alt|Shift|0||エディターのレイアウトを切り替える（水平/垂直）
Ctrl|||=/-||ズームイン/ズームアウト
Ctrl|||B||サイドバーの表示を切り替え
Ctrl||Shift|E||エクスプローラーを表示/フォーカスを切り替え
Ctrl||Shift|F||検索を表示
Ctrl||Shift|G||ソース管理を表示
Ctrl||Shift|D||デバッグを表示
Ctrl||Shift|X||拡張機能を表示
Ctrl||Shift|H||ファイルで置き換える
Ctrl||Shift|J||Toggle検索の詳細
Ctrl||Shift|U||出力パネルを表示
Ctrl||Shift|V||Markdownプレビューを開く
Ctrl|||K|(Z)|Zenモード（Esc Escで終了）
{{</ table >}}

### デバッグ

{{< table class="table table-hover table-condensed " >}}

Ctrl|Alt|Shift|他のキー1|他のキー2|機能
---|---|---|---|---|---
||||F9||ブレークポイントを切り替え
||||F5||開始/続行
|||Shift|F5||やめる
||||F11||ステップイン/ステップアウト
|||Shift|F11||ステップイン/ステップアウト
||||F10||ステップオーバー
Ctrl|||K|I|ホバーを表示

{{</ table >}}

以上です。最後まで読んでいただきありがとうございました。

関連語句：キーボードショートカット一覧, 短縮キー一覧, ファンクションキー一覧, Keyboard shortcuts,VSCode（ブイエスコード）
