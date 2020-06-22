# 音乐解析

### 接口说明
解析指定的音乐平台的歌曲直链，暂时仅支持网易云，其他待添加


### 接口文档

接口链接:`http://api.huokuoluo.cn/api/wyy/api.php`

返回格式:`MP3`  请求方式:`GET`

### 请求参数

|  名称  |  类型  |  必填  |  说明  |
|  :----:  |  :----:  |  :----:  |  :----:  |
|id|String|是|指定音乐ID|

### 返回参数

|名称|类型|说明
|:----:|:----:|:----:|
|MP3|null|无参数，直接返回音乐|

### 请求示例

`1:`http://api.huokuoluo.cn/api/wyy/api.php?id=28859948
分享Young Rising Sons的单曲《Turnin'》: http://music.163.com/song/`28859948`/?userid=516481829 (来自@网易云音乐)

### 返回示例
<audio controls>
  <source src="http://api.huokuoluo.cn/api/wyy/api.php?id=28859948" type="audio/mpeg">
您的浏览器不支持 audio 元素。
</audio>
`<audio controls><source src="http://api.huokuoluo.cn/api/wyy/api.php?id=28859948" type="audio/mpeg">您的浏览器不支持 audio 元素。</audio>`

