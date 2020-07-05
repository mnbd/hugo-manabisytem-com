---
title: "Value-domain（バリュードメイン）の独自ドメインをNetlifyに設定する方法"
date: 2020-06-08T13:51:17+09:00
summary: "Value-Domain（バリュードメイン）で管理する独自ドメインをホスティングサービス Netlify に設定する方法をご紹介いたします。"
categories: [""]
tags: ["ウェブ/ホームページ制作"]
draft: false
url: "/how-to-set-up-custom-domain-with-value-domain-and-netlify"
---

Value-Domain（バリュードメイン）で管理する独自ドメインをホスティングサービス Netlify に設定する方法をご紹介いたします。

## 前提

以下の項目につきましては完了済みであることとしています。

- Netlify のアカウント取得
- Netlify でサイト公開
- Value-domain のアカウント取得
- Value-domain でドメイン購入

## 1. Netlifyの設定

### 1. 独自ドメインを設定したいサイトを選択する

teamのホーム画面から独自ドメインを設定したいサイトを選択して Overview 画面を表示します。

{{< img src="2020-06-08-screenshot-00001.png" alt="Netlifyのteam画面">}}

### 2. 独自ドメインを設定するメニューを選択

「Set up a custom domain」を選択します。

{{< img src="2020-06-08-screenshot-00002.png" alt="siteのOverview画面">}}

### 3. 独自ドメインを追加する

「Domain management」メニューから「Add custom domain」をクリックしてください。

{{< img src="2020-06-08-screenshot-00003.png" alt="Domain managementメニュー画面" >}}

### 4. 設定したい独自ドメインを設定

設定する独自ドメインを入力して Verify ボタンを押してください。
例：manabisystem.com

{{< img src="2020-06-08-screenshot-00004.png" alt="Custom domain入力画面1" >}}

{{< img src="2020-06-08-screenshot-00005.png" alt="Custom domain入力画面2" >}}

### 5. Netlifyのネームサーバーのアドレスを取得する

設定した独自ドメインの右側にある「Options」をクリックして、「Set up」を選択してください。

{{< img src="2020-06-08-screenshot-00006.png" alt="Custom domains画面" >}}

「Domain Settings」画面の「Nameservers」の項目にあるネームサーバーのアドレスを全て保存してください。

{{< img src="2020-06-08-screenshot-00007.png" alt="DNS Settings画面" >}}

## 2. Value-domainの設定

### 1. ネームサーバーの設定

Value-domain にログインして、コントロールパネルを表示してください。

「ネームサーバーの設定」をクリックしてください。

{{< img src="2020-06-08-screenshot-00008.png" alt="コントロールパネル画面" >}}

### 2. 変更するドメインを選択

変更するドメインの右側のボタンをクリックして、「変更」ボタンを押してください。

{{< img src="2020-06-08-screenshot-00009.png" alt="ネームサーバー設定画面" >}}

### 3. Netlify のネームサーバーを設定

先ほどの 1-5 で取得した Netlify のネームサーバーを全て入力して、「保存する」ボタンを押してください。

{{< img src="2020-06-08-screenshot-00010.png" alt="ネームサーバー設定画面" >}}

## 3. Netlify の設定を再度確認

独自ドメインを設定したサイトの Overview 画面の「Domain settings」をクリックしてください。

{{< img src="2020-06-08-screenshot-00011.png" alt="Overview 設定画面" >}}

設定した独自ドメインの項目に「 Netlify DNS 」と表示されていることを確認してください。

{{< img src="2020-06-08-screenshot-00012.png" alt="Custom domains 設定画面" >}}

ブラウザから独自ドメインでアクセスしてみて表示されていれば完了です。

## 参考

- {{< exlink href="https://www.value-domain.com/" text="バリュードメイン" >}}
- {{< exlink href="https://www.netlify.com/" text="Netlify" >}}

以上です。読んでいただきありがとうございました。
