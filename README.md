# elasticsearch-study

Elasticsearchの勉強用(Docker環境)

## What is Elasticsearch?

ElasticsearchはOSSの分散処理マルチテナント対応検索エンジン  
超高速に全文検索を行うことができる

[製品ページ](https://www.elastic.co/jp/products/elasticsearch)  
[GitHubリポジトリ](https://github.com/elastic/elasticsearch)

### [主なアクセス方法]

- HTTP RESTful API
- Native Java API(ソース自体はJavaで書かれているため)

### [ユースケース]

- システムのログを蓄積し、分析する
- 社内リソースの高速検索
- ECサイトの商品を高速検索

## What is Kibana?

Elasticsearchのデータを分析・可視化するツール。  
クエリの発行や分析結果のグラフ表示が行える。

---

## 開発環境(遊び場)構築

Dockerを使用してElasticsearchとKibanaをサクッと準備する

