---
title: "LINE ログインチャネルの作成"
---

# プロバイダーの作成

# チャネル作成
- ログイン
https://developers.line.biz/ja/services/line-login/ にアクセス。
「今すぐはじめよう」のボタンを押して進めていきましょう。
![](https://storage.googleapis.com/zenn-user-upload/kk09ycv3181bxkla6mi8vozaysvd)

「LINEアカウントでログイン」を押してください。
![](https://storage.googleapis.com/zenn-user-upload/70l8v8t5cnxm8n9mnehecct8ade5 =250x)

LINEのログインを求められるのでログインしてください。
![](https://storage.googleapis.com/zenn-user-upload/s9upjzix36rvx4rupi00ardmz0s6 =250x)

- チャネルの種類
LINEログインになっているか確認します。
![](https://storage.googleapis.com/zenn-user-upload/tu6u2hc6g83thpcqgrdkw3se4ph7 =500x)

- プロバイダ
既にプロバイダーを作っている場合 → 利用するプロバイダーを選択しましょう。
![](https://storage.googleapis.com/zenn-user-upload/ygq2jt08ywonwjy8ki5ap8rirtc7 =500x)
初めて → 新規プロバイダー作成を選択しプロバイダー名を入力しましょう。
（LINEという文字は含められません。）
![](https://storage.googleapis.com/zenn-user-upload/ertfact9pdh71pu2xgwtu2uv2d0y =600x)

- 地域、チャネルアイコン
地域は「日本」、チャネルアイコンを登録しましょう。（今回は必須ではありません）
![](https://storage.googleapis.com/zenn-user-upload/bsd3zk5de6uwrjuygwzooxzwa9mb =600x)

- チャネル名、チャネル説明
下記を入力しましょう。
チャネル名：「テーブルオーダー」
チャネル説明：「テーブルオーダー」
![](https://storage.googleapis.com/zenn-user-upload/97icg052ett2dzquwan8l68pelsa)

- アプリタイプ
アプリタイプは「ウェブアプリ」にチェックをつけましょう。
![](https://storage.googleapis.com/zenn-user-upload/xi654rczexr7dabdutg5uj5ljrjw)

- メールアドレス、プライバシーポリシーURL、サービス利用規約URL
メールアドレスを確認しましょう。
プライバシーポリシーURLとサービス利用規約URLは入力しないで大丈夫です。
![](https://storage.googleapis.com/zenn-user-upload/99cgwnkz1s27xti6jtakdg87ijdr)

- 作成
下記 開発者契約に同意し、チェックをして「作成」ボタンを押しましょう。
![](https://storage.googleapis.com/zenn-user-upload/o6zjh4ihmtazma4lm2xxs0qvclix)

# チャネル基本設定

- リンクされたボット
さきほど作成したMessagingAPIのチャネルを選択し、更新を行います。
![](https://storage.googleapis.com/zenn-user-upload/kqpp92ez0ipj52f8kllb2dtk0yc4)
![](https://storage.googleapis.com/zenn-user-upload/271pv8l6h46sm9nis22la12tjqii)

# LIFFの作成
- 作成
「LIFF」タブに移動して「追加」ボタンを押しましょう。
![](https://storage.googleapis.com/zenn-user-upload/lafgohpi6jrva9gfltyej6073a5u)

- LIFFアプリ名、サイズ
LIFFアプリ名は「テーブルオーダー」、サイズは「Full」を選択しましょう。
![](https://storage.googleapis.com/zenn-user-upload/22b3fcomq2wm2adzumynfubekgto)

- エンドポイントURL
エンドポイントURLは仮で「https://example.com 」と入力します。URLが決まったら変更します。
![](https://storage.googleapis.com/zenn-user-upload/1cwbw25kf8chkf7rx56zt72ura10)

- Scope
Scopeは「profile」とすべて表示をクリックし、「chat_message.write」にチェックをつけましょう。
![](https://storage.googleapis.com/zenn-user-upload/ojmcafkfz0yc9njc15b60c2eh7wn)

- ボットリンク機能
ボットリンク機能は「On」にチェックをつけて、「追加」ボタンを押しましょう。
![](https://storage.googleapis.com/zenn-user-upload/3qin3g2dilsn0k3e3io8j27kai9p)

- LIFF ID と LIFF URL
LIFF ID と LIFF URL をメモしましょう。
![](https://storage.googleapis.com/zenn-user-upload/xept4q6oi29q68tba0v05yteek86)

