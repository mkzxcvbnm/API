# nav

> 导航

---

{% method %}

## 请求URL

    http://域名/index.php/Api/nav

## 参数

|参数名|别名|类型|默认值|说明|
|:----:|:--:|:--:|:----:|:--:|
|typeid|类型|number|`必填`|`1`-主导航 `2`-尾导航 `3`-全部|
|limit|显示数量|number|`null`|&nbsp;|

{% sample lang="THML" %}

## 例子

**请求示例**

> http://www.yunucms.cn/index.php/api/nav?typeid=1

**响应示例**

```json
{
    "state": 200,
    "info": "请求成功",
    "data": [
    {
        "target": "_self",
        "url": "http:\/\/www.yunucms.cn\/guanyuwomen\/"
    },
    {
        "target": "_self",
        "url": "http:\/\/www.yunucms.cn\/chanpinzhanshi\/"
    },
    {
        "target": "_self",
        "url": "http:\/\/www.yunucms.cn\/xinwenzhongxin\/"
    },
    {
        "target": "_self",
        "url": "http:\/\/www.yunucms.cn\/kehuanli\/"
    },
    {
        "target": "_self",
        "url": "http:\/\/www.yunucms.cn\/lianxiwomen\/"
    }]
}
```

{% endmethod %}
