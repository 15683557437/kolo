# 舔狗日记

### <i class="fas fa-home fa-fw"></i>接口说明
随机返回一句古诗词，带出处


### 接口文档

接口链接:`http://api.huokuoluo.cn/api/gushici/api.php`

返回格式:`JSON/TEXT`  请求方式:`GET`

### 请求参数

|  名称  |  类型  |  必填  |  说明  |
|  :----:  |  :----:  |  :----:  |  :----:  |
|type|String|是|aiqing(爱情类) qita(其他类) chun(春天类) xia(夏天类)全部类无需参数|

### 返回参数

|名称|类型|说明
|:----:|:----:|:----:|
|JSON/TEXT|String|返回的JSON/文本|

### 请求示例

`1:`http://api.huokuoluo.cn/api/gushici/api.php?type=chun
`2:`http://api.huokuoluo.cn/api/gushici/api.php?type=aiqing

### 返回示例
`document.write("红酥手，黄縢酒，满城春色宫墙柳。－－陆游《钗头凤·红酥手》");`

### 实例演示
<iframe src="http://api.2kolo.cn/api/gushici/" height="600" width="100%" farmeborder="no" border="0"></iframe>