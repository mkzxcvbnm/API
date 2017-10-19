# content

> 获取详情页信息

{% method %}
**参数**

|参数名|别名|类型|默认值|说明|
|:----:|:--:|:--:|:----:|:--:|
|cid|栏目ID|number|`必填`|后台非单页模型栏目ID 或者 `$cid`-当前栏目id|
|titlelen|标题长度|number|`0`|`0`-不截取|
|orderby|排序|string|`id desc`|`asc`-正序 `desc`-倒序|
|keyword|关键词|string|`空`|模糊查询title(标题)字段|
|limit|显示数量|number|`10`|当设置了`pagesize`时,该参数无效|
|pagesize|分页数|number|`0`|配合`{$page}`使用,生成分页|
|flag|标示|bool|`false`|`true`-推荐 `false`-全部|
|top |头条|number|`0`|`0`-非头条 `1`-一级头条 ..... `9`-九级头条|
|tag |标签|number|`0`|(内容详情页专属)`0`-不筛选 `1`-筛选条件增加当前详情的tag值|


{% sample lang="THML" %}

**响应结果**

```html

```

{% endmethod %}
