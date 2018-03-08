# content

> 获取详情页信息

---

{% method %}

## 请求URL

    http://域名/index.php/Api/content

## 参数

|参数名|别名|类型|默认值|说明|
|:----:|:--:|:--:|:----:|:--:|
|id|内容ID|number|`必填`|详情页内容的ID编号|


{% sample lang="HTML" %}

## 例子

**请求示例**

> http://www.yunucms.cn/index.php/api/content?id=30

**响应示例**

```json
{
    "state": 200,
    "info": "请求成功",
    "data":
    {
        "id": 30,
        "cid": 29,
        "mid": 35,
        "title": "案例1",
        "jumpurl": "",
        "etitle": "",
        "click": 118,
        "vid": 1,
        "sort": 0,
        "istop": 1,
        "create_time": 1506676928,
        "update_time": 1506676947,
        "aid": 1,
        "seo_title": "案例1",
        "seo_keywords": "建筑装饰五金,机械五金件,手动工具,电动工具",
        "seo_desc": null,
        "area": "",
        "top": 0,
        "pic": "\/\/www.yunucms.cn\/uploads\/image\/20170929\/8c181da0f27dc6671dd5ec70453f9117.jpg",
        "tag": "",
        "conid": 1,
        "piclist": "",
        "desc": "<p>1<\/p>",
        "content": "<p>1<\/p>",
        "ys_title": "案例1",
        "url": "http:\/\/www.yunucms.cn\/kehuanli\/30.html",
        "prev": "没有了",
        "next": "<a href='http:\/\/www.yunucms.cn\/kehuanli\/31.html'>案例2<\/a>",
        "category":
        {
            "id": 29,
            "title": "客户案例",
            "etitle": "kehuanli",
            "subtitle": "",
            "pid": 0,
            "mid": 35,
            "pic": "",
            "seo_title": "",
            "seo_keywords": "",
            "seo_desc": "",
            "jumpurl": "",
            "tpl_cover": "",
            "tpl_list": "list_picture.html",
            "tpl_show": "show_product.html",
            "sort": 4,
            "status": 1,
            "target": 0,
            "nav": 1,
            "desc": "<p>这里是案例简介设置这里是案例简介设置这里是案例简介设置这里是案例简介设置这里是案例简介设置这里是案例简介设置这里是案例简介设置这里是案例简介设置这里是案例简介设置这里是案例简介设置这里是案例简介设置这里是案例简介设置<\/p>",
            "content": "",
            "cover": 0,
            "isarea": 0
        }
    }
}
```

{% endmethod %}
