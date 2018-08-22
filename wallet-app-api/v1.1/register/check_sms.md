# 注册--验证验证码  --- 这不是我要的结果

请求地址 */register/check_sms*

请求方式 **POST**

请求参数
- mobile 类型 *string*
- username 类型 *string* 值等于mobile
- smscode 类型 *string*

参数说明
```
// 短信验证key 
$smsKey = '你吼呀靓仔';
```

返回参数
```
{
	"code": 0,
	"msg": "请求成功！",
	"data": {
		"smsKey": "你吼呀靓仔"
	},
	"lang": 0,
	"token": "sdfasfdfafd221100",
	"datetime": "2018-03-01 11:09:56"
}
```
