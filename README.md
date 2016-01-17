# comet-asynchronized

非同期型でcometを実装するサンプル

* サーバ側
    - CountUpServletのcount変数を5sごとにインクリメントします。

* クライアント側
    - /countUpにブラウザからアクセスすると更新があったタイミングで結果が戻ります。

# ポイント
* Servlet3.0から提供された非同期APIを利用した
* クライアントは通信が終了したら即座にサーバに再接続しにいく

# 起動方法

* mvn tomcat7:run
