---
title: "動作確認"
---

# LIFFのエンドポイントを変更

LINEログインのチャネル設定画面でLIFFのエンドポイントURLに、バックエンドの構築手順でメモしたCloudFrontDomainNameの値を設定して「更新」ボタンを押してください。

![](https://storage.googleapis.com/zenn-user-upload/4xntpxietdrhyrsm4boio81g7zyq)

![](https://storage.googleapis.com/zenn-user-upload/lrh9ijjsrso23ze5wekt41rjltce)

# LIFF公開する

「非公開」ボタンを押します。
![](https://storage.googleapis.com/zenn-user-upload/mhgpfl6m6a6bd2gliq0pwfgio8kc =500x)

「公開」ボタンを押します。
![](https://storage.googleapis.com/zenn-user-upload/4ith4uysdvcsmv24zq13gb0i523a =500x)


# リッチメニューの作成
- リッチメニュー設定
Messaging API のチャネル基本設定画面でLINE Official Account Managerに移動します。
![](https://storage.googleapis.com/zenn-user-upload/9kg3ra1mdhtiic9fti3zt2xxl6xd)
ホーム→トーク管理→リッチメニュー→作成の順にクリックしましょう。
![](https://storage.googleapis.com/zenn-user-upload/ibwgawlq1fyc7b701c6429d8vlzm)

- 表示設定
下記のように設定しましょう。
![](https://storage.googleapis.com/zenn-user-upload/oc4iy453c1ntkcn83qc6x0wfvehk)

- テンプレート
次に、「テンプレートを選択」を押します。小の一番下を選択して、「選択」ボタンを押しましょう。
![](https://storage.googleapis.com/zenn-user-upload/ln4cuzjkvw9u4pyr8vo03p6e8tbx)

- 画像作成
次に、「画像を作成」を押します。リッチメニューの画像を作成できるので、お好みの背景色を選んでください。
![](https://storage.googleapis.com/zenn-user-upload/e656pkyqwvg9z3pg5mcu3ynecp8d)

「テキストを追加」を押して「テーブルオーダー」と入力します。中央揃えをして整えましょう。
![](https://storage.googleapis.com/zenn-user-upload/iqu6vsafms5jhakycd5p6f4ka5fq =500x)

できたら「適用」ボタンを2回押しましょう。（「ファイルに保存」ボタンを押すと画像としてダウンロードできます。）
![](https://storage.googleapis.com/zenn-user-upload/qc9gp5lzbnyyaq0ydwqhc3wcjejb =500x)

- アクション設定
次にアクションを設定します。タイプを「リンク」にして、LIFF作成時にメモした「LIFF URL」を入力し、保存しましょう。
![](https://storage.googleapis.com/zenn-user-upload/a69an2l4o2tae3qauwigsbw3bjg6)

# データの登録
- DynamoDBのコンソール画面にアクセス
下記のURLからDynamoDBのコンソール画面を開き、先ほど作成したテーブルを開き、項目の作成ボタンを押します。
https://ap-northeast-1.console.aws.amazon.com/dynamodb/home?region=ap-northeast-1#tables:selected=ItemListDB;tab=items
![](https://storage.googleapis.com/zenn-user-upload/5xtnded86oxfy70aahw4ilgcoh8r)

- 項目の作成画面でデータを登録
下記のURLにアクセスしjsonのデータを全てコピーし、項目の作成画面の左上のセレクトボックスを`Text`にした後、先ほどコピーしたjsonデータをペーストしてください。
https://raw.githubusercontent.com/jaws-ug-kanazawa/line-api-use-case-table-order/master/backend/APP/dynamodb_data/table_order_item_0.json
![](https://storage.googleapis.com/zenn-user-upload/6zk3nlfdp559odgo5mbgj0jwejgk)

- データ登録の確認
データが正常に登録されたか、データレコードができていることを確認してください。
![](https://storage.googleapis.com/zenn-user-upload/aod7nnsaredu1n1ujaygr90moaax)

# 動作確認しましょう！

全ての準備は整いました！アプリを起動し動作確認してみてください！

https://youtu.be/TyCiag2ekIc
