# area

> 地区导航

{% method %}

## 请求URL

    http:/域名/index.php/Api/area

## 参数

|参数名|别名|类型|默认值|说明|
|:----:|:--:|:--:|:----:|:--:|
|top|是否推荐|number|`0`|`0`-全部 `1`-开启推荐|
|con|独立内容|number|`0`|`0`-全部 `1`-开启独立内容|
|url|二级域名|number|`0`|`0`-全部 `1`-开启二级域名|
|limit|显示数量|number|`null`|&nbsp;|

{% sample lang="THML" %}

## 例子

**请求示例**

> http://www.yunucms.cn/index.php/api/area?limit=5

**响应示例**

```json
{
    "state": 200,
    "info": "请求成功",
    "data": [
    {
        "id": 34,
        "title": "台湾省",
        "stitle": "台湾",
        "etitle": "taiwan",
        "pid": 0,
        "sort": 0,
        "istop": 1,
        "iscon": 0,
        "isurl": 1,
        "url": "http:\/\/taiwan.yunucms.cn"
    },
    {
        "id": 2,
        "title": "上海市",
        "stitle": "上海",
        "etitle": "shanghai",
        "pid": 0,
        "sort": 0,
        "istop": 1,
        "iscon": 0,
        "isurl": 1,
        "url": "http:\/\/shanghai.yunucms.cn"
    },
    {
        "id": 3,
        "title": "天津市",
        "stitle": "天津",
        "etitle": "tianjing",
        "pid": 0,
        "sort": 0,
        "istop": 1,
        "iscon": 0,
        "isurl": 1,
        "url": "http:\/\/tianjing.yunucms.cn"
    },
    {
        "id": 4,
        "title": "重庆市",
        "stitle": "重庆",
        "etitle": "chongqing",
        "pid": 0,
        "sort": 0,
        "istop": 1,
        "iscon": 0,
        "isurl": 1,
        "url": "http:\/\/chongqing.yunucms.cn"
    },
    {
        "id": 5,
        "title": "广东省",
        "stitle": "广东",
        "etitle": "guangdong",
        "pid": 0,
        "sort": 0,
        "istop": 1,
        "iscon": 0,
        "isurl": 1,
        "url": "http:\/\/guangdong.yunucms.cn"
    }]
}
```

{% endmethod %}
