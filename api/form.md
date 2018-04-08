#form

> 获取form

---

{% method %}

## 请求URL

http://域名/index.php/Api/form

## 参数

|参数名|别名|类型|默认值|说明|
|:----:|:--:|:--:|:----:|:--:|
|\_\_formid\_\_|表单ID|number|`必填`|对应 后台 > 扩展管理 > 表单管理 > ID|
|name|联系人|自定义|`可选`|对应 后台 > 扩展管理 > 表单管理 > 字段管理 > 字段名|
|phone|手机|自定义|`可选`|同上|
|yuanwang|你的留言|自定义|`可选`|同上|
|\_\_captcha1\_\_|验证码|string|`必填`|**注意`captcha`后的数字需与`__formid__`一致**|

{% sample lang="HTML" %}

## 例子

**验证码生成**

```html
<img src="<yunu:url name='captcha' id='1'>" onclick="this.src='<yunu:url name='captcha' id='1'>'" />
```

**请求示例**

> http://www.yunucms.cn/index.php/Api/form?__formid__=1&name=*&phone=*&yuanwang=*&__captcha1__=aaaa

**响应示例**

```json
{
    "state": 200,
    "info": "请求成功"
}
```

{% endmethod %}