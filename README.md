## 目的

藉由 Content-base Filtering 的方式進行商品推薦，並搭配 User Profile 進行補強

## 結果

- 使用 Title 或 Description 作為 Content-base filter 的訓練資料並搭配近三個月的 rule-base filtering，擁有同樣的結果，比起直接使用 Rule-base 推薦分數下降了 0.3%

## 思考過程

- 原始資料中適合用做 Content-base filtering 的資料欄位為 Title 以及 description
- 在 Testing data 中，只有 38/584 有購買記錄，因此絕大多數並不適用於 Content-base filtering 的場景，因此搭配上週的 Rule-base filtering 進行推薦
