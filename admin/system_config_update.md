
## 简要描述

- 系统配置更新接口

## 请求URL
- `http://localhost:9887/api/admin/config`

## 请求方式
- POST
- application/json

## 请求示例

```json
{
    "webSiteName": "Thin Wiki", 
    "webSiteDescription": "Thin Wiki", 
    "webSiteKeywords": "Thin Wiki", 
    "resourceBaseUrlType": "local"
}
```

## 参数

|参数名|类型|说明|
|:-----  |:-----|-----                           |
|code |int   |返回码，0-正常，1-异常  |
|msg |string   | 返回消息  |
|webSiteName |string   | 网站标题  |
|webSiteDescription |string   | 网站描述  |
|webSiteKeywords |string   | 网站关键字  |
|resourceBaseUrlType |string   | 网站资源基本路径，值有 local,jsdelivr,custom 三类  |

## 返回示例

``` json
{
    "code": 0, 
    "msg": "success"
}
```

## 返回参数说明

|参数名|类型|说明|
|:-----  |:-----|-----                           |
|code |int   |返回码，0-正常，1-异常  |
|msg |string   | 返回消息  |



