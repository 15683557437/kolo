# 二维码生成

### 接口说明

获取定义的链接,文案，系统生成二维码图片返回

### 接口文档

接口链接:`http://api.2kolo.cn/api/qrcode/api.php`

返回格式:`IMG`  请求方式:`GET`

### 请求参数

|  名称  |  类型  |  必填  |  说明  |
|  :----:  |  :----:  |  :----:  |  :----:  |
|text|String|是|二维码内容，链接需带协议头(http://|https://)|
|size|String|选填|二维码大小，单位是px|

### 返回参数

|名称|类型|说明
|:----:|:----:|:----:|
|img|null|无参数，直接返回图片|

### 请求示例

`1:`http://api.huokuoluo.cn/api/qrcode/api.php?text=我喜欢你&size=120

`2:`http://api.huokuoluo.cn/api/qrcode/api.php?text=https://2kolo.cn&size=120

### 返回示例
![alt 返回示例](http://api.huokuoluo.cn/api/qrcode/api.php?text=https://2kolo.cn&size=120 "随机头像")