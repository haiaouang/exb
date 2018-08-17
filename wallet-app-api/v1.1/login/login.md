# 登陆  --- 看鸡毛

请求地址 */login*

请求方式 **POST**

请求参数
- username 类型 *string*
- password 类型 *string*

参数说明
```
// 手机号码 
$mobile = "13111111111";

// 设置二级密码 1 已设置 0 未设置
$hasSecpwd = 0;

// 是否机构 1 是 0 不是
$isMech = 0;
```

返回参数
```
{
	"code": 0,
	"msg": "请求成功！",
	"data": {
		"userInfo": {
			"id": 1,
			"username": "user1",
			"mobile": "13111111111",
			"address": "",
			"balance": "0",
			"hasSecpwd": 0,
			"isMech": 0
		}
	},
	"lang": 0,
	"token": "sdfasfdfafd221100",
	"datetime": "2018-03-01 11:09:56"
}
```
