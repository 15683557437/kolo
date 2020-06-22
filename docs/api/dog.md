# 舔狗日记

### <i class="fas fa-home fa-fw"></i>接口说明
随机展示主题为舔狗日记的文字


### 接口文档

接口链接:`http://api.huokuoluo.cn/api/tiangou/api.php`

返回格式:`JSON/TEXT`  请求方式:`GET`

### 请求参数

|  名称  |  类型  |  必填  |  说明  |
|  :----:  |  :----:  |  :----:  |  :----:  |
|charset|String|否|UTF-8字符编码|
|encode|String|否|JS输出|

### 返回参数

|名称|类型|说明
|:----:|:----:|:----:|
|JSON/TEXT|String|返回的JSON/文本|

### 请求示例

`1:`http://api.huokuoluo.cn/api/tiangou/api.php?charset=utf-8
`2:`http://api.huokuoluo.cn/api/tiangou/api.php?encode=js

### 返回示例
`document.write("今天你跟我说我很丑，让我不要骚扰你了。我听了很高兴，小说里的主角都像你这样，最开始表现的很厌恶，但最后总会被我的真心打动。你现在有多讨厌我，以后就会有多爱我。嘻嘻。");`

### 实例演示
<iframe src="http://api.2kolo.cn/api/tiangou/" height="600" width="100%" farmeborder="no" border="0"></iframe>