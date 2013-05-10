これは何？
----

ECプラットフォーム提供サービスの [Shopify](http://www.shopify.com) が公開しているオープンソースのダッシュボード用フレームワーク [Dashing](http://shopify.github.io/dashing) で作成したサンプルプロジェクトです。

詳しくは[モダンなダッシュボード用フレームワークDashing入門](http://blog.qnyp.com/2013/05/09/try-dashing/)をご覧ください。

[デモサイトはこちら](http://qnyp-blog-try-dashing.herokuapp.com/sample)です。

必要なもの
----
* Ruby 1.9 or 2.0
* [Bundler](http://gembundler.com/)


開発環境で確認
----

ダウンロードして bundle インストールします。
```
$ git clone git@github.com:qnyp/qnyp-blog-try-dashing.git
$ cd qnyp-blog-try-dashing
$ bundle
```

`dashing`コマンドで起動します。

```
$ dashing start
```

次のような起動メッセージが表示され、[localhost:3030](localhost:3030)で確認できます。

```
>> Thin web server (v1.5.1 codename Straight Razor)
>> Maximum connections set to 1024
>> Listening on 0.0.0.0:3030, CTRL+C to stop
```
