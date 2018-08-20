# 机构--信息获取  --- 来呀来呀你来呀！

请求地址 */mech/show*

请求方式 **GET**

参数说明
```
// 是否机构 1 是 0 不是
$isMech = 0;

// 审核状态 0 未申请 （1 - 8） 申请中 -1 被驳回 9 已通过
// $isMech = 1 时可忽略改字段 
$auditStatus = 0;
```

返回参数
```
{
	"code": 0,
	"msg": "请求成功！",
	"data": {
		"isMech": 0,
		"auditStatus": 0
	},
	"lang": 0,
	"token": "sdfasfdfafd221100",
	"datetime": "2018-03-01 11:09:56"
}
```
