# banner

> 幻灯片

{% method %}

## 请求URL

    http:/域名/index.php/Api/banner

## 参数

|参数名|别名|类型|默认值|说明|
|:----:|:--:|:--:|:----:|:--:|
|type|类型|number|`0`|`0`-全部 `1`-PC `2`-手机|
|orderby|排序|string|`id desc`|`asc`-正序 `desc`-倒序|
|limit|显示数量|number|`null`|&nbsp;|

{% sample lang="THML" %}

## 例子

**请求示例**

> http://www.yunucms.cn/index.php/api/banner

**响应示例**

```json
{
    "state": 200,
    "info": "请求成功",
    "data": [
    {
        "id": 20,
        "title": "11",
        "pic": "\/uploads\/image\/20170929\/c20ee6e4f167f19eb37754c6178d8f21.jpg",
        "fpic": "",
        "url": "#",
        "sort": 0,
        "type": 2
    },
    {
        "id": 19,
        "title": "11",
        "pic": "\/uploads\/image\/20170929\/b6d3bf29720455ef16903e8689fcb4bb.jpg",
        "fpic": "",
        "url": "#",
        "sort": 0,
        "type": 2
    },
    {
        "id": 18,
        "title": "22",
        "pic": "\/uploads\/image\/20170929\/a01b7740cb8c75cff837c8a8baad3c3e.jpg",
        "fpic": "",
        "url": "#",
        "sort": 0,
        "type": 1
    },
    {
        "id": 17,
        "title": "11",
        "pic": "\/uploads\/image\/20170929\/eb242765015da7ac79987234e12b2d3c.jpg",
        "fpic": "",
        "url": "#",
        "sort": 0,
        "type": 1
    }]
}
</yunu:banner>
```

{% endmethod %}
