---
title: "Netlify に独自ドメインのサブドメインで複数サイトを公開する方法"
date: 2020-06-08T16:55:46+09:00
categories: [""]
tags: ["ウェブ/ホームページ制作"]
summary: "ホスティングサービスNetlifyで独自ドメインのサブドメインを利用して複数のサイトを公開する方法をご紹介いたします。"
draft: false
url: "/how-to-set-up-websites-with-sub-domain-for-netlify"
---

Netlify で独自ドメインのサブドメインを設定してサイトを公開する方法をご紹介いたします。

## 前提

以下の条件をご理解いただいている方を前提としています。

- Netlifyでの独自ドメインの設定
- Netlifyでのサイト公開（デプロイ）の設定
- 公開するサイトのGitリポジトリの設定

## 1. サイトの作成

Netlify のログイン画面でタイトルの「 ～'s team 」をクリックしてください。

「New site from Git」ボタンを押してください。

{{< img src="2020-06-08-screenshot-00013.png" alt="サイト管理画面" >}}

作成するサイトに関連付けるリポジトリのサービスを選択してください。

{{< img src="2020-06-08-screenshot-00014.png" alt="Gitサービス選択画面" >}}

選択したGitリポジトリによって、ビルドコマンドやパブリッシュディレクトリを設定してください。

{{< img src="2020-06-08-screenshot-00015.png" alt="デプロイ設定画面" >}}

## 2. サブドメインの設定

「Domain settings」をクリックしてください。

{{< img src="2020-06-08-screenshot-00016.png" alt="ドメイン設定画面" >}}

「Domains」の項目から「Add custom domain」を設定してください。

{{< img src="2020-06-08-screenshot-00017.png" alt="ドメイン選択画面" >}}

サブドメイン付きの独自ドメインを入力してVerfyをクリックしてください。

例：blog.manabisystem.com

{{< img src="2020-06-08-screenshot-00018.png" alt="ドメイン設定画面" >}}

「Yes, add domain」をクリックしてください。ｓ

{{< img src="2020-06-08-screenshot-00019.png" alt="ドメイン設定画面" >}}

## 3. SSL(HTTPS)の設定

この設定は、あらかじめ独自ドメインが設定されていて、HTTPSの設定が完了している場合です。

「Force HTTPS」ボタンをクリックしてください。

{{< img src="2020-06-08-screenshot-00020.png" alt="HTTPS設定画面" >}}

「Force HTTPS」ボタンをクリックしてください。

{{< img src="2020-06-08-screenshot-00021.png" alt="HTTPS設定画面" >}}

ブラウザでサブドメインにアクセスできるかどうか確認してみてください。

## 参考

- {{< exlink href="https://www.netlify.com" text="Netlify" >}}

以上です。読んでいただきありがとうございました。
