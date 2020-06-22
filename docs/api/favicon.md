# Fav图标获取

### <i class="fas fa-home fa-fw"></i>接口说明

获取指定网站的Favicon图标

### 接口文档

接口链接:`http://api.huokuoluo.cn/api/fav/get.php`

返回格式:`IMG`  请求方式:`GET`

### 请求参数

|  名称  |  类型  |  必填  |  说明  |
|  :----:  |  :----:  |  :----:  |  :----:  |
|url|String|是|需要获取图标的URL地址，如：http://api.huokuoluo.cn|

### 返回参数

|名称|类型|说明
|:----:|:----:|:----:|
|ico/img|null|无参数，直接返回图片|

### 请求示例

`1:`http://api.huokuoluo.cn/api/fav/get.php?url=http://api.huokuoluo.cn

### 返回示例
![alt 返回示例](http://api.huokuoluo.cn/api/fav/get.php?url=http://api.huokuoluo.cn "Favicon")