# QQ信息

### 接口说明
查询指定QQ的基本及看点信息


### 接口文档

接口链接:
`1(QQ基本信息):http://api.huokuoluo.cn/api/qqcx/api.php`
`2(QQ看点信息)http://api.huokuoluo.cn/api/qqcx/kdapi.php`

返回格式:`JSON`  请求方式:`GET`

### 请求参数

|  名称  |  类型  |  必填  |  说明  |
|  :----:  |  :----:  |  :----:  |  :----:  |
|qq|String|是|QQ号码|

### 返回参数

|名称|类型|说明
|:----:|:----:|:----:|
|imgurl|String|头像链接|
|name|String|QQ昵称(不显示表情字符)|

|名称|类型|说明
|:----:|:----:|:----:|
|看点信息|String|看点昵称,QQ,签名,被赞数,动态,关注,粉丝|

### 请求示例

`1:`http://api.huokuoluo.cn/api/qqcx/api.php?qq=QQ号码
`2:`http://api.huokuoluo.cn/api/qqcx/kdapi.php?qq=QQ号码

### 返回示例
`{"code":1,

"imgurl":"https://q.qlogo.cn/headimg_dl?dst_uin=QQ&spec=100",

"name":"昵称"}`
`{"看点昵称":"昵称","QQ":"QQ","签名":"","被赞数":"0","动态":"0","关注":"1","粉丝":"0"}`
