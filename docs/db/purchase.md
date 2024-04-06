# 購入マスタ

### 物理名:purchase

|項目名|物理名|データ型|主キー|インデックス|外部キー参照|NULL許可|備考|
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|購入ID|purchase_id|Integer|○|-|-|-|Auto increment|
|顧客ID|customer_id|String|-|-|Customer.customer_id|-|-|
|日付|date|DateTime|-|-|-|-|-|