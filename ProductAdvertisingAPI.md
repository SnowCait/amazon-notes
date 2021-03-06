# Product Advertising API

## v5
- [Product Advertising API 5.0](https://webservices.amazon.com/paapi5/documentation/)
  - [PA-API v5移行のご案内](https://affiliate.amazon.co.jp/help/node/topic/GZBFW3F79Y7FADBL)
  - [API Rates · Product Advertising API 5.0](https://webservices.amazon.com/paapi5/documentation/troubleshooting/api-rates.html)
  - [Japan · Product Advertising API 5.0](https://webservices.amazon.com/paapi5/documentation/locale-reference/japan.html)
- [Product Advertising API (PA-API) に専用のIAMでアクセスする - Qiita](https://qiita.com/kyo_nanba/items/2fcb8b22ef36c74802e3)
- [【Rails】Amazon PA API v5.0 で書籍検索 - Qiita](https://qiita.com/koki_73/items/da9f2ed01aadd6394702)
- [[PA-API5.0]Amazon APIでオリジナルのランキング一覧表示スクリプトを作る - めめんと](https://mementoo.info/archives/4053)
- [Amazonカテゴリ一覧 23,420 件（BrowseNodeデータ収集結果） - Qiita](https://qiita.com/kobake@github/items/88001f62983211027f63)

## Sandbox
- [Product Advertising API 5.0 Scratchpad](https://webservices.amazon.co.jp/paapi5/scratchpad/index.html)

## Library
- [nager/Nager.AmazonProductAdvertising: .NET Amazon Product Advertising Client](https://github.com/nager/Nager.AmazonProductAdvertising)

### 代替 API

- ほしいものリスト
  - [doitlikejustin/amazon-wish-lister: Retrieve Amazon Wishlist and output to JSON, XML, or PHP Array Object](https://github.com/doitlikejustin/amazon-wish-lister)

## API Reference

### Operations

|operation|Required Parameter|説明|
|---|---|---|
|GetBrowseNodes|BrowseNodeIds|ブラウズノード情報を取得|
|GetVariations|ASIN|ASIN からバリエーション違いのアイテム情報を取得|
|GetItems|ItemIds|アイテム ID からアイテム情報を取得|
|[SearchItems](./pa-api/SearchItems.md)|Keywords, Actor, Artist, Author, Brand or Title|クエリからアイテムを検索|

### Resources

|resource|説明|
|---|---|
|BrowseNodeInfo||
|BrowseNodes||
|Images||
|ItemInfo||
|Offers||
|ParentASIN||
|SearchRefinements||
|VariationSummary||
