# 短视频解析

### 接口说明
解析指定的短视频平台无水印视频直链，暂时仅支持抖音，其他待添加


### 接口文档

接口链接:`http://api.2kolo.cn/api/dsp/dyapi.php`

返回格式:`JSON`  请求方式:`GET`

### 请求参数

|  名称  |  类型  |  必填  |  说明  |
|  :----:  |  :----:  |  :----:  |  :----:  |
|url|String|是|视频分享链接|

### 返回参数

|名称|类型|说明
|:----:|:----:|:----:|
|title|String|视频标题|
|url|String|视频封面链接|
|url|String|视频直链|

### 请求示例

`1:`http://api.2kolo.cn/api/dsp/dyapi.php?url=https://v.douyin.com/J8dpCCR

### 返回示例
`{"code":"101","msg":"获取成功,阔落API提供!","data":{"title":"补一个竖屏","img":"https://p9-dy.byteimg.com/img/tos-cn-p-0015/f07bfabf0b454241956a6d17f1430939~c5_300x400.jpeg?from=2563711402_large","url":"http://v3-dy.ixigua.com/4a855527433c46b0f176c69ab5db7148/5ef0eb20/video/tos/cn/tos-cn-ve-15/09c3dc07f2a345cd9327c9ed66ebc25c/?a=1128&br=5049&bt=1683&cr=0&cs=0&dr=0&ds=3&er=&l=202006230032040100140470880E72783D&lr=&mime_type=video_mp4&qs=0&rc=am88eWUzOjlxdTMzNmkzM0ApMzg8aWk1Nzs8N2RpZWZpOWdsMHNib3JmaWdfLS02LS9zcy9hYy81MTQuYzZhXzIxXy86Yw%3D%3D&vl=&vr="}}set 限制解除译`

### 实例演示
[可乐去水印](http://shui.2kolo.cn/)
