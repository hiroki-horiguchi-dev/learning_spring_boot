# 転職先で使うかもしれないので入門してみた
- RestApi を作れるやつからお試し
- DB と繋がないと意味ないからそこから続きをやろう
- 一日2つくらいのペースで進めてみる
- 裏ですごい色々とやってくれるみたいで実装自体は全然難しくなさそう

# RestApis
1. [Building a RESTful Web Service
   ](https://spring.pleiades.io/guides/gs/rest-service) ✅
   1. ルーティングとコントローラーとみたいなところを学んだ
   2. URL のクエリパラメータ取る方法とかも学んだ
   3. @SpringBootApplication ちょっとむずい
      1. 3つくらい説明があったけど、すぐ理解できたのは自動 DI をするための仕組みぽいということ
      2. Bean という構成要素を Spring Boot に覚えさせるって説明だったね
2. [RetTemplateでRestAPIの利用](https://spring.pleiades.io/guides/gs/consuming-rest)
3. [HATEOASでハイパーメディア駆動REST APIの作成](https://spring.pleiades.io/guides/gs/rest-hateoas) ✅
   1. HATEOAS String の使い方の説明
   2. アクセスされたURLから新しいURLを作成して返せまっせって話だった
   3. つまり、HATEOASを使うことで、APIのインターフェースが動的に整備できるというのが重要なポイント(chatgpt)
   4. ![img.png](img.png)
4. [Spring Boot アプリケーションの構築
   ](https://spring.pleiades.io/guides/gs/spring-boot) ✅
   1. コントローラーに設定したルーティングで適当なページの表示
   2. 及びそのリンクに対する単体テスト、結合テストとか
5. [Spring Data Rest API の自動生成(Neo4j)](https://spring.pleiades.io/guides/gs/accessing-neo4j-data-rest) ✅
   1. [いきなりグラフデータベース～人生で初めてNeo4jを触ってみた（Cypher入門）
      ](https://recruit.gmo.jp/engineer/jisedai/blog/graph-database-neo4j-try-cypher/)
   2. Neo4j: SNS(linkedin のような)に使われるノードと矢印を用いたデータベース構造
   3. 金融系などでも使われており、これのおかげで不正なデータ間のつながりを検知することができる
   4. この章で扱う Neo4j サーバーは、提供するアプリケーションで Neo4j DB が使われている前提で、このDB を楽に操作するためのライブラリという捉え方で良い
   5. また、3章の HATEOAS と組み合わせることで、例えばSNSアプリにおいては誰と誰がつながっているのか？などを表すハイパーリンクを作成することが用意となる
   6. この章では主にその方法について記述がある
6. [Spring Data Rest API の児童生絵師(Gemfire)](https://spring.pleiades.io/guides/gs/accessing-gemfire-data-rest)
   1. 初見は全然わからんが、自動生成してくれる何かなんだろう
7. [HATEOASでREST API の構築](https://spring.pleiades.io/guides/tutorials/rest)
8. [WebFlux REST API と WebClient](https://spring.pleiades.io/guides/gs/reactive-rest-service)