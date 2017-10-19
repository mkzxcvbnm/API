# position

> 当前位置(面包屑导航)

{% method %}

## 请求URL

    http:/域名/index.php/Api/position

## 参数

|参数名|别名|类型|默认值|说明|
|:----:|:--:|:--:|:----:|:--:|
|cid|栏目ID|number|`必填`|后台栏目ID|
|sname|末尾链接名称|string|`空`||
|surl|末尾链接地址|string|`空`||
|delimiter|分隔符|string|`&gt;&gt;`|设置所有链接之间的间隔符|

{% sample lang="THML" %}

## 例子

**请求示例**

> http://www.yunucms.cn/index.php/api/position?cid=20

**响应示例**

```json
{
    "state": 200,
    "info": "请求成功",
    "data": "<a href=\"http:\/\/www.yunucms.cn\/\">首页<\/a>&gt;&gt;<a href=\"http:\/\/www.yunucms.cn\/guanyuwomen\/\">关于我们<\/a>"
}
```

{% endmethod %}
