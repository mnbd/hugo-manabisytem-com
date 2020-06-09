---
title: "NetlifyとHugoで構築したサイトにお問い合わせフォームをつける方法"
date: 2020-06-09T14:40:43+09:00
summary: "静的サイトジェネレーター「Hugo」とホスティングサービス「Netlify」で構築したサイトにお問い合わせフォームをつける方法をご紹介いたします。"
categories: ["サイト制作"]
tags: ["Netlify","Hugo"]
url: "/how-to-add-contact-form-on-netlify"
draft: true
---

静的サイトジェネレーター「Hugo」とホスティングサービス「Netlify」で構築したサイトにお問い合わせフォームをつける方法をご紹介いたします。

Netlifyのフォームサービスを利用いたします。無料から利用できますが、条件がありますのでご注意ください。

## 前提

以下の条件をご理解していただいている前提でご紹介させていただきます。

- HugoとNetlifyでサイト構築ができている
- ページの新規作成ができる

## 料金と制限

Netlifyのフォームサービスには利用制限があります。100通/月までは無料です。

{{< img src="2020-06-09-screenshot-00006.png" >}}

## フォーム用のショートコード作成

/layout/shortcodes/のディレクトリに「form.html」という名前で以下の内容のファイルを作成します。

```html
<form name="contact" method="POST" data-netlify="true">
  <p>
    <label>お名前: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label>E-Mail: <input type="email" name="email" /></label>
  </p>
  <p>
    <label>内容: <textarea name="message"></textarea></label>
  </p>
  <p>
    <button type="submit">送信</button>
  </p>
</form>
```

## マークダウンファイルに記述

お問い合わせ用ページのマークダウンファイルの例です。

```markdown
---
title: "お問い合わせ"
date: 2020-06-09T11:45:13+09:00
draft: false
---

まなびシステムへのご連絡は以下のフォームよりお願いいたします。

内容によっては返信をご遠慮させていただく場合や諸事情により返信に時間がかかる場合がございますことをご了承ください。

{{</* form */>}}
```

## フォーム内容の受け取りの流れ

公開したサイトのフォームに内容を入力して送信します。

{{< img src="2020-06-09-screenshot-00003.png" >}}

### 1. 送信成功のメッセージ表示

送信が成功すると以下のようなメッセージが表示されます。

{{< img src="2020-06-09-screenshot-00001.png" >}}

### 2. NetlifyのOverview画面でメッセージ受信

NetlifyのサイトのOverview画面の左下にメッセージが届きます。

メッセージをクリックしてください。

{{< img src="2020-06-09-screenshot-00002.png" >}}

### 3. メッセージの詳細を表示

{{< img src="2020-06-09-screenshot-00004.png" >}}

## メールで通知

問い合わせがあった段階でメールに内容を通知することができます。

### 1. Formsメニューを表示

上のタブメニューから「Settings」をクリックしてください。

{{< img src="2020-06-09-screenshot-00005.png" >}}

### 2. E-mail notificationを選択

左のメニューから「Forms」をクリックしてください。

「E-mail notification」をクリックしてください。

{{< img src="2020-06-09-screenshot-00007.png" >}}

### 3. E-mail to notifyにメールアドレスを記入

「E-mail to notify」の項目に受信したいメールアドレスを記入して、「Save」ボタンを押してください。

{{< img src="2020-06-09-screenshot-00009.png" >}}

以下のように表示されれば完了です。

{{< img src="2020-06-09-screenshot-00008.png" >}}

お問い合わせフォームから送信するとメールが届きます。

以上です。読んでいただきありがとうございました。
