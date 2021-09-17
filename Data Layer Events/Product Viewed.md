# Product Viewed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "Product Viewed",
    "items": [
        {
            "discount": "<discount>",
            "item_id": "<item_id>",
            "item_name": "<item_name>",
            "price": "<price>"
        }
    ]
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|discount|number|Monetary value of discount associated with a purchase.|2.22|||||||
|item_id|string|Item ID \(context-specific\).The product primary ID \(SKU or UPC\) |SKU\_12345|||||||
|item_name|string|Item Name \(context-specific\).|jeggings|||||||
|price|number|The monetary price of the item, in units of the specified currency parameter.|9.99|||||||



