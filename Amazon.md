# Amazon

## ASIN

- [Amazon.co.jp ヘルプ: ISBN/ASINについて](https://www.amazon.co.jp/gp/help/customer/display.html?nodeId=201889580)

## URL

- [Amazon.co.jpの正規化URLの構造を調べてみた - 風柳メモ](https://memo.furyutei.work/entry/20141018/1413593100)
- [Amazon、qid、URL、意味｜独り言｜素人翻訳](http://goutou.mamagoto.com/%E7%8B%AC%E3%82%8A%E8%A8%80/amazon%E3%80%81qid%E3%80%81url%E3%80%81%E6%84%8F%E5%91%B3)
- [What's the meaning of Amazon's URL? - Stack Overflow](https://stackoverflow.com/questions/20610070/whats-the-meaning-of-amazons-url/40978204)
```
rh denotes the factors of query.
k = keyword,
n = category (Sports & Outdoors in this case)
p_n_condition-type = new/used
p_n_date = 発売日
p_72 = 4 or more stars
p_85 = prime eligible
page = pagination offset(page nos).
qid = the timestamp when the query result was generated.
bbn = browse node numbers.Amazon uses a hierarchy of nodes with a number to the hierarchy to represent collections of items. Each number given is a browse node number.
rnid = random id  for browsing the node.
ie=utf8 = UTF-8 page encoding format.
```

### Parameters

|parameter|place|説明|
|---|---|---|
|dp|path|ASIN `/dp/[ASIN]/`|
|k|query|検索キーワード|
|coliid|query|プロダクトの ID っぽいが不明|
