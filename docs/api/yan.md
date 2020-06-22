# 随机一言

### 接口说明
随机返回一句话，多类型


### 接口文档

接口链接:`http://api.huokuoluo.cn/api/tiangou/api.php`

返回格式:`TEXT`  请求方式:`GET`

### 请求参数

|  名称  |  类型  |  必填  |  说明  |
|  :----:  |  :----:  |  :----:  |  :----:  |
|type|String|是|aiqing(爱情类) wenyi(文艺类) dujitang(毒鸡汤类) jingshen(精神语录类)|

### 返回参数

|名称|类型|说明
|:----:|:----:|:----:|
|TEXT|String|返回的一句话文本|

### 请求示例

`1:`http://api.huokuoluo.cn/api/yan/api.php?type=dujitang
`2:`http://api.huokuoluo.cn/api/yan/api.php?type=jingshen

### 返回示例
`都说谈恋爱会影响学习，难道学习，就不影响谈恋爱吗？`

### 实例演示
<iframe src="http://api.2kolo.cn/api/gushici/" height="600" width="100%" farmeborder="no" border="0"></iframe>