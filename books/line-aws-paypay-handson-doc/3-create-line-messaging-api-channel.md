---
title: "Messaging API チャネルの作成"
---

# プロバイダーの作成
# チャネルの作成
- チャネルの作成
https://developers.line.me/ja/services/messaging-api/ にアクセス。
「今すぐはじめよう」のボタンを押して進めていきましょう。
![](https://storage.googleapis.com/zenn-user-upload/a1qsm1lazwwh93c222ykd417kps9)

- チャネルの種類
Messaging APIになっているか確認します。
![](https://storage.googleapis.com/zenn-user-upload/dnrwequtv83nuabrkdtxm0i5nriv =500x)

- プロバイダ
LINEログインで使用したプロバイダーを選択しましょう。
![](https://storage.googleapis.com/zenn-user-upload/ygq2jt08ywonwjy8ki5ap8rirtc7 =500x)

- チャネルアイコン
チャネルアイコンを登録しましょう。（今回は必須ではありません）
![](https://storage.googleapis.com/zenn-user-upload/youjo9avqsk8jv7qioxwmbzw6pot)

- チャネル名、チャネル説明
下記を入力しましょう。
チャネル名：「テーブルオーダーBot」
チャネル説明：「テーブルオーダーBot」
![](https://storage.googleapis.com/zenn-user-upload/r0icjkwqtdbtamoyu2mjlhfiq089)

- 大業種、小業種
大業種と小業種は個人を選択しましょう。（リスト下の方にあります。）
![](https://storage.googleapis.com/zenn-user-upload/gc4u5lqitwjo9j2r342al0hjys42)

- メールアドレス、プライバシーポリシーURL、サービス利用規約URL
メールアドレスを確認しましょう。
プライバシーポリシーURLとサービス利用規約URLは入力しないで大丈夫です。
![](https://storage.googleapis.com/zenn-user-upload/99cgwnkz1s27xti6jtakdg87ijdr)

- 作成
下記２点の利用規約にチェックをして「作成」ボタンを押しましょう。
![](https://storage.googleapis.com/zenn-user-upload/lhz3bpwtb5995j1u4mlt99t5a43k)
「OK」を押しましょう。
![](https://storage.googleapis.com/zenn-user-upload/f2hi57quav5nokkasjk23anlemjf =500x)
「同意する」を押しましょう。
![](https://storage.googleapis.com/zenn-user-upload/38b40kfsidf073w30w2m494pnemh =500x)


# リッチメニューの作成
- リッチメニュー設定
LINE Official Account Managerに移動します。
![](https://storage.googleapis.com/zenn-user-upload/9kg3ra1mdhtiic9fti3zt2xxl6xd)
ホーム→トーク管理→リッチメニュー→作成の順にクリックしましょう。
![](https://storage.googleapis.com/zenn-user-upload/ibwgawlq1fyc7b701c6429d8vlzm)

- 表示設定
下記のように設定しましょう。
※画像追加する

- テンプレート
次に、「テンプレートを選択」を押します。小の一番下を選択して、「選択」ボタンを押しましょう。
![](https://storage.googleapis.com/zenn-user-upload/ln4cuzjkvw9u4pyr8vo03p6e8tbx)

- 画像作成
次に、「画像を作成」を押します。リッチメニューの画像を作成できるので、お好みの背景色を選んでください。
![](https://storage.googleapis.com/zenn-user-upload/e656pkyqwvg9z3pg5mcu3ynecp8d)
「テキストを追加」を押して「xxx」と入力します。
※画像追加する
できたら「適用」ボタンを押しましょう。（「ファイルに保存」ボタンを押すと画像としてダウンロードできます。）
※画像追加する

- アクション設定
次にアクションを設定します。タイプを「リンク」にして、LIFF作成時にメモした「LIFF URL」を入力し、保存しましょう。
※画像追加する

# LINE BOTと友だちになる
- QRコードで友だち追加
LINE Developersに戻り「Messaging API設定」タブに移動し、QRコードを読み取って、友だち追加をしましょう。
![](https://storage.googleapis.com/zenn-user-upload/zixpwvkcvi2xrjj5w0xvt4kl30z5)

- 確認
リッチメニューが設置されていてウェルカムメッセージが来たら成功です。
