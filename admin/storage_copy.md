
## 请求URL
- `http://localhost:9887/api/admin/storage/{storageId}/copy`

## 请求方式
- PUT
- application/json

## 请求示例

``` json
{
    "refStorageType": "LOCAL", 
    "refStorageId": 1000, 
}
```

## 请求参数

|参数名|类型|说明|
|:-----  |:-----|-----|
|storageId |string   | 存储id，请求URL中的{storageId}  |
|refStorageType |string   | 存储类型，有LOCAL、GITEE、GITHUB，分别对应本地存储、gitee存储、github存储  |
|refStorageId |int   | 对应的存储类型id  |

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




