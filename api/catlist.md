# catlist

> 栏目列表

---

{% method %}

## 请求URL

    http://域名/index.php/Api/catlist

## 参数

|参数名|别名|类型|默认值|说明|
|:----:|:--:|:--:|:----:|:--:|
|cid|栏目ID|number|`必填`|后台栏目ID 或者 `$cid`-当前栏目id|
|type|类型|string|`son`|`son`-下级栏目 `self`-同级栏目 `top`-顶级栏目|
|limit|显示数量|number|`null`||
|flag|标示|number|`1`|`0`-不显示外部链接和单页 `1`-全部|

{% sample lang="THML" %}

## 例子

**请求示例**

> http://www.yunucms.cn/index.php/api/catlist?cid=21&limit=2

**响应示例**

```json
{
    "state": 200,
    "info": "请求成功",
    "data": [
    {
        "id": 22,
        "title": "建筑装饰五金",
        "etitle": "jianzhuzhuangshiwujin",
        "subtitle": "",
        "pid": 21,
        "mid": 34,
        "pic": "",
        "seo_title": "",
        "seo_keywords": "",
        "seo_desc": "",
        "jumpurl": "",
        "tpl_cover": "",
        "tpl_list": "list_product.html",
        "tpl_show": "show_product.html",
        "sort": 1,
        "status": 1,
        "target": 0,
        "nav": 0,
        "desc": "<p>建筑五金建筑物或构筑物中装用的金属和非金属制品、配件的总称。一般具有实用和装饰双重效果。<\/p>",
        "content": "",
        "cover": 0,
        "isarea": 1,
        "url": "http:\/\/www.yunucms.cn\/jianzhuzhuangshiwujin\/",
        "child": [
        {
            "id": 35,
            "title": "建筑五金",
            "etitle": "jianzhuwujin",
            "subtitle": "",
            "pid": 22,
            "mid": 34,
            "pic": "",
            "seo_title": "",
            "seo_keywords": "",
            "seo_desc": "",
            "jumpurl": "",
            "tpl_cover": "",
            "tpl_list": "list_product.html",
            "tpl_show": "show_product.html",
            "sort": 0,
            "status": 1,
            "target": 0,
            "nav": 0,
            "desc": "<p>建筑五金建筑物或构筑物中装用的金属和非金属制品、配件的总称。一般具有实用和装饰双重效果。<\/p>",
            "content": "",
            "cover": 0,
            "isarea": 1,
            "url": "http:\/\/www.yunucms.cn\/jianzhuwujin\/",
            "child": []
        },
        {
            "id": 36,
            "title": "装饰五金",
            "etitle": "zhuangshiwujin",
            "subtitle": "",
            "pid": 22,
            "mid": 34,
            "pic": "",
            "seo_title": "",
            "seo_keywords": "",
            "seo_desc": "",
            "jumpurl": "",
            "tpl_cover": "",
            "tpl_list": "list_product.html",
            "tpl_show": "show_product.html",
            "sort": 0,
            "status": 1,
            "target": 0,
            "nav": 0,
            "desc": "",
            "content": "",
            "cover": 0,
            "isarea": 1,
            "url": "http:\/\/www.yunucms.cn\/zhuangshiwujin\/",
            "child": []
        }]
    },
    {
        "id": 23,
        "title": "机械五金件",
        "etitle": "jixiewujinjian",
        "subtitle": "",
        "pid": 21,
        "mid": 34,
        "pic": "",
        "seo_title": "",
        "seo_keywords": "",
        "seo_desc": "",
        "jumpurl": "",
        "tpl_cover": "",
        "tpl_list": "list_product.html",
        "tpl_show": "show_product.html",
        "sort": 2,
        "status": 1,
        "target": 0,
        "nav": 0,
        "desc": "<p>五金：传统的五金制品，也称“小五金”。指金、银、铜、铁、锡五种金属。经人工加工可以制成刀、剑等艺术品或金属器件。现代社会的五金更为广泛，例如五金工具、五金零部件、日用五金、建筑五金以及安防用品等。小五金产品大都不是最终消费品。<\/p>",
        "content": "",
        "cover": 0,
        "isarea": 1,
        "url": "http:\/\/www.yunucms.cn\/jixiewujinjian\/",
        "child": [
        {
            "id": 38,
            "title": "机械五金",
            "etitle": "jixie",
            "subtitle": "",
            "pid": 23,
            "mid": 34,
            "pic": "",
            "seo_title": "",
            "seo_keywords": "",
            "seo_desc": "",
            "jumpurl": "",
            "tpl_cover": "",
            "tpl_list": "list_product.html",
            "tpl_show": "show_product.html",
            "sort": 0,
            "status": 1,
            "target": 0,
            "nav": 0,
            "desc": "",
            "content": "",
            "cover": 0,
            "isarea": 1,
            "url": "http:\/\/www.yunucms.cn\/jixie\/",
            "child": []
        }]
    }]
}
```

{% endmethod %}
