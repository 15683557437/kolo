# 随机壁纸

### 接口说明

随机返回各种类型的壁纸图片，分手机及电脑

### 接口文档

接口链接:`http://api.2kolo.cn/api/sjbz/api.php`

返回格式:`IMG`  请求方式:`GET`

### 请求参数

|  名称  |  类型  |  必填  |  说明  |
|  :----:  |  :----:  |  :----:  |  :----:  |
|  lx  |  String  |  是  |  dongman(动漫)   meizi(美女)   fengjing(风景)   suiji(随机)
|method|String|选填|mobiel(手机端)   pc(电脑端)|

### 返回参数

|名称|类型|说明
|:----:|:----:|:----:|
|img|null|无参数，直接返回图片|

### 请求示例

`1:`http://api.huokuoluo.cn/api/sjtx/api.php?lx=dongman

`2:`http://api.huokuoluo.cn/api/sjbz/api.php?method=mobile&lx=suiji

### 返回示例
![alt 返回示例](http://api.huokuoluo.cn/api/sjbz/api.php?method=mobile&lx=suiji "随机壁纸")