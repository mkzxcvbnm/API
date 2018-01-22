# API

Yunu API文档

---

{% method %}

## 请求URL格式

    http://域名/index.php/Api/版本号/API接口名称

> 版本号为可选 默认调用master接口

> 推荐在url中带上版本号，可以避免因API升级带来的兼容问题

> 当前最新版本为`V1`

> [历史文档地址](https://mkzxcvbnm.gitbooks.io/api/content/)


## 请求方式

* GET/POST

## 服务器返回数据类型

* json/jsonp

## 返回状态state

|状态码|别名|
|:----:|:--:|
|`200`|请求成功|
|`400`|请求失败|

{% sample lang="THML" %}

### json例子

**请求示例**

> http://www.yunucms.cn/index.php/api/config?name=seo_title

**响应示例**

```json
{
    "state": 200,
    "info": "请求成功",
    "data": "建筑装饰五金,机械五金件,手动工具,电动工具"
}
```

### jsonp例子

**请求示例**

> http://www.yunucms.cn/index.php/Api/config?name=seo_title&callback=callback_function

**响应示例**

```json
callback_function({
    "state": 200,
    "info": "请求成功",
    "data": "建筑装饰五金,机械五金件,手动工具,电动工具"
});
```

**js示例**
```js
$.ajax({
    url: "http://www.yunucms.cn/index.php/Api/config",
    type: "POST",
    dataType: "jsonp",
    data: {
        name: "seo_title"
    },
    beforeSend: function(jqXHR) {
        console.log(jqXHR);
    }
}).done(function(res) {
    if (res.state == 200) {
        console.log("请求成功");
    }else{
        console.log(res.info);
    }
}).fail(function(jqXHR, textStatus) {
    console.log("error");
}).always(function() {
    console.log("complete");
});
```

{% endmethod %}
