# Page Load Started

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "Page Load Started",
    "page_title": "<page_title>",
    "page_type": "<page_type>"
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|page_title|string|The title of the page currently being viewed, generally available in &lt;title&gt;.||||||||
|page_type|string|The type of page currently viewed.|home, pdp, article|||||||



