RESTって何？
REST(Representational State Transfer)とは、Web APIの開発において標準的なアーキテクチャです。
RESTとは、ステートレスなクライアントとサーバーの関係を意味します。それはサーバーから取得されいるクライアントのコンテキストがない他の多くのアプローチとは異なるという意味です。
それとは逆に、RESTの場合、各リクエストはユーザの認証のために必要なすべての情報を持つ必要があります。
そしてどんなセッションデータをしっかりと送信しなければいけません。

RESTを使うメリットは、既に存在しているHTTPアーキテクチャにHTTPリクエストメソッドを適用できるところです。
これらの操作は、以下のような操作から構成されています。

    GET - サーバーから基本的なデータ取得するときに使われます。
    PUT- サーバーに既に存在しているオブジェクトの変更をするときに使われます。
    POST- サーバーに新しくオブジェクトを作成するときに使われます。
    DELETE - サーバーから既存のオブジェクトを取り除くときに使われます。

これらの操作を利用するURIエンドポイントを作ることで、RESTful APIはすぐに出来上がります。