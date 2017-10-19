# url

> 获取url

---

{% method %}

## 请求URL

    http://域名/index.php/Api/url

## 参数

|参数名|别名|类型|默认值|说明|
|:----:|:--:|:--:|:----:|:--:|
|name|名称|string|`必填`|[点击查看](#name)|

<span id="name">**name**</span>

|值|别名|说明|
|:-:|:--:|:--:|
|home|网站首页|生成网站首页网址|
|search|搜索页面|生成搜索页面网址|

{% sample lang="THML" %}

## 例子

**请求示例**

> http://www.yunucms.cn/index.php/api/url?name=home

**响应示例**

```json
{
    "state": 200,
    "info": "请求成功",
    "data": "http:\/\/www.yunucms.cn\/"
}
```

{% endmethod %}
