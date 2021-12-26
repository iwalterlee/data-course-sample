## 目的

建立推薦系統，以提升轉換率。預期可達到 10% 的推薦分數。

## 結果，是否有成功：

本次專案中嘗試了兩種思維，皆不成功，最高的推薦分數為 8.3%。

兩個推薦規則與思考方向

- 第一種推薦模式：直接推薦訓練期間前十最多 review 的產品 (0.08305084745762711)
- 第二種推薦模式：透過產品推送產品 (0.0)
    - 首先先觀察購買者的的 review histogram，發現有一則以上產品回饋的消費者佔極低的比例，因此直接使用該消費者的消費史做為推薦方式並不實際，邏輯改成為消費過同樣產品的消費者其餘購買過的產品最為推薦列表。