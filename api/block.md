# block

> 自定义块

{% method %}

## 请求URL

    http:/域名/index.php/Api/block

## 参数

|参数名|别名|类型|默认值|说明|
|:----:|:--:|:--:|:----:|:--:|
|name|标题|string|`必填`|自定义块名称|
|infolen|内容长度|number|`0`|`0`-不截取 **注意：**图片或丰富类型自定义块勿使用此属性|
|textflag|内容类型|number|`0`|`1`-输出为img `0`-输出内容|

{% sample lang="THML" %}

## 例子

**请求示例**

> http://www.yunucms.cn/index.php/api/block?name=logo

**响应示例**

```json
{
    "state": 200,
    "info": "请求成功",
    "data": "<img src=\"\/uploads\/image\/20170929\/583f583fa9414bed1f230809411004dd.png\" \/>"
}
```

{% endmethod %}
