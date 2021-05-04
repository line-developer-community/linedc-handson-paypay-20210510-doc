---
title: "動作確認"
---

# LIFFのエンドポイントを変更

LINEログインのチャネル設定画面でLIFFのエンドポイントURLに、バックエンドの構築手順でメモしたCloudFrontDomainNameの値を設定してください。

![](https://storage.googleapis.com/zenn-user-upload/4xntpxietdrhyrsm4boio81g7zyq)

![](https://storage.googleapis.com/zenn-user-upload/lrh9ijjsrso23ze5wekt41rjltce)

# データの登録
- DynamoDBのコンソール画面にアクセス
下記のURLからDynamoDBのコンソール画面を開き、先ほど作成したテーブルを開き、項目の作成ボタンを押します。
https://ap-northeast-1.console.aws.amazon.com/dynamodb/home?region=ap-northeast-1#tables:selected=ItemListDBName;tab=items
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

