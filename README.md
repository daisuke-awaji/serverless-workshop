# serverless-workshop

![serverless workshop architecture](./score-board.png)

開発者（参加者）は SQS に送信された情報を集計するシステムを構築します。

# アンケート集計システム

冬といえば
1, クリスマス
2, 雪
3, こたつ
のような csv ファイルが飛んでくる
SQS に投入されたデータをいち早く集計し、結果をランキングごとに出力できたチームが優勝

評価項目は以下
集計までのスピード　（60-処理時間）分 × 100 ポイント
正確さ　全て正解　 5000 ポイント　一位だけ正解 3000 ポイント
