# Googleコネクテッドシート

## BigQuery公開データセットを読み込む

![alt text](images/image.png)

![alt text](images/image-1.png)

![alt text](images/image-2.png)

![alt text](images/image-3.png)

![alt text](images/image-4.png)

![alt text](images/image-5.png)

![alt text](images/image-6.png)

![alt text](images/image-7.png)

## ピボットテーブルを使った分析

![alt text](images/image-8.png)

![alt text](images/image-9.png)

![alt text](images/image-10.png)

![alt text](images/image-11.png)

![alt text](images/image-12.png)

- 苦情が発生した都市の割合が高い順に並んだ

![alt text](images/image-13.png)

- 列に`complaint_type` を追加し、苦情の種類の内訳が分かるようにする
    - 書籍では列数を50としていたが、もう少し絞らないと空白の多いテーブルになってしまったので5件とした

![alt text](images/image-14.png)

- `BROOKLIN` , `BRONX` , `NEW YORK` では`Noise Residential` (住宅の騒音)が最も多いが、`STATEN ISLAND` では`Street Condition` (路上の状態)が最も多いことがわかる

![alt text](images/image-15.png)

## コネクテッドシートでグラフを追加してみる

![alt text](images/image-16.png)

![alt text](images/image-17.png)

![alt text](images/image-18.png)

![alt text](images/image-19.png)

![alt text](images/image-20.png)

## コネクテッドシートのまとめ

- BigQueryのテーブルに対するスプレッドシート上での集計がかなり簡単に実現されていた
- 実務でも「ちょっとデータの分布を可視化したい」などで使えそう

![alt text](images/image-21.png)

![alt text](images/image-22.png)

![alt text](images/image-23.png)

![alt text](images/image-24.png)