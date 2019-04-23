# list

> 内容列表

---

{% method %}

## 请求URL

    http://域名/index.php/Api/list

## 参数

|参数名|别名|类型|默认值|说明|
|:----:|:--:|:--:|:----:|:--:|
|cid|栏目ID|number|`必填`|后台非单页模型栏目ID|
|titlelen|标题长度|number|`0`|`0`-不截取|
|orderby|排序|string|`id desc`|`asc`-正序 `desc`-倒序|
|keyword|关键词|string|`空`|模糊查询title(标题)字段|
|limit|显示数量|number|`null`|不传此参数默认调取所有数据|
|pages|分页数|number|`1`|配合`limit`使用,获取对应分页数的数据|
|flag|标示|number|`0`|`1`-推荐 `0`-全部|
|top |头条|number|`0`|`0`-非头条 `1`-一级头条 ..... `9`-九级头条|
<!-- |tag |标签|number|`0`|(内容详情页专属)`0`-不筛选 `1`-筛选条件增加当前详情的tag值| -->

{% sample lang="php" %}

**请求示例**

> http://www.yunucms.cn/index.php/api/list?cid=35&limit=2&pages=2

**响应示例**

```json
{
    "state": 200,
    "info": "请求成功",
    "data": [
    {
        "id": 47,
        "cid": 35,
        "mid": 34,
        "title": "22-FHE-SB",
        "jumpurl": "",
        "etitle": "",
        "click": 13,
        "vid": 10,
        "sort": 0,
        "istop": 1,
        "create_time": 1508129404,
        "update_time": 1508129425,
        "aid": 1,
        "seo_title": "",
        "seo_keywords": "",
        "seo_desc": "",
        "area": "",
        "top": 0,
        "pic": "\/\/www.yunucms.cn\/uploads\/image\/20171016\/7f0f09c6dc95a402dd0272041c3f81ec.jpg",
        "tag": "",
        "url": "http:\/\/www.yunucms.cn\/jianzhuwujin\/47.html"
    },
    {
        "id": 46,
        "cid": 35,
        "mid": 34,
        "title": "FHB200-BG",
        "jumpurl": "",
        "etitle": "",
        "click": 53,
        "vid": 9,
        "sort": 0,
        "istop": 1,
        "create_time": 1508129374,
        "update_time": 1508129402,
        "aid": 1,
        "seo_title": "",
        "seo_keywords": "",
        "seo_desc": "",
        "area": "",
        "top": 0,
        "pic": "\/\/www.yunucms.cn\/uploads\/image\/20171016\/77e467ecd89008cdb7045fc638cc8e1d.jpg",
        "tag": "",
        "url": "http:\/\/www.yunucms.cn\/jianzhuwujin\/46.html"
    }]
}
```

{% endmethod %}
