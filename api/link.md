# link

> 友情链接

{% method %}

## 请求URL

    http:/域名/index.php/Api/link

## 参数

|参数名|别名|类型|默认值|说明|
|:----:|:--:|:--:|:----:|:--:|
|type|类型|number|`1`|`1`-首页 `2`-内页 `3`-其他|
|orderby|排序|string|`id desc`|`asc`-正序 `desc`-倒序|
|limit|显示数量|number|`null`|不传此参数默认调取所有数据|
|flag|标示|number|`0`|`1`-有图片 `0`-无图片|

{% sample lang="THML" %}

## 例子

**请求示例**

> http://www.yunucms.cn/index.php/api/link

**响应示例**

```json
{
    "state": 200,
    "info": "请求成功",
    "data": [
    {
        "id": 6,
        "title": "百度",
        "pic": "",
        "url": "http:\/\/www.baidu.com",
        "sort": 0,
        "type": 1,
        "area": ""
    },
    {
        "id": 5,
        "title": "搜狗",
        "pic": "",
        "url": "http:\/\/www.sogou.com",
        "sort": 0,
        "type": 1,
        "area": ""
    }]
}
```

{% endmethod %}
