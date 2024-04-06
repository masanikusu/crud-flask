# 購入詳細マスタ

### 物理名:purchase_details

|項目名|物理名|データ型|主キー|インデックス|外部キー参照|NULL許可|備考|
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|購入ID|purchase_id|String|○|-|Purchase.purchase_id|-|-|
|商品ID|item_id|String|○|-|Item.item_id|-|-|
|数量|quantity|Integer|-|-|-|-|-|