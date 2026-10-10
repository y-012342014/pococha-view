# pococha-view

Pococha のイベントのポイント差を見るだけのページです。

このリポジトリにあるのは静的な HTML 1 枚だけで、データは入っていません。
表示のたびに、配信者側の PC で動いている読み取り専用サーバへ直接問い合わせます（約 1 秒ごと）。

見るには、接続先と合い言葉を付けた URL が必要です。

    https://<ユーザー名>.github.io/pococha-view/?api=https://<ホスト>.ts.net&k=<合い言葉>

一度開けば、接続先と合い言葉はブラウザに保存されます（localStorage）。
URL を知らない人、合い言葉を持っていない人には何も表示されません。

作成: pococha-tracker（D:\Pなど\pococha-tracker\public-page\index.html が元）
