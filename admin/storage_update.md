
## 请求URL
- `http://localhost:9887/api/admin/storage/{storageId}`

## 请求方式
- PUT
- application/json

## 请求示例

``` json
{
    "name": "本地存储", 
    "description": "本地存储", 
    "workType": "MAIN"
    "mainStorageId": null
    "writable": false
}
```

## 请求参数

|参数名|类型|说明|
|:-----  |:-----|-----|
|storageId |string   | 记录id，请求URL中的{storageId}  |
|name |string   | 名字  |
|description |string   | 描述  |
|workType |string   | 工作类型，有MAIN，BACKUP  |
|mainStorageId |int   | 只有workType=BACKUP时才有意义，主节点id，workType=MAIN类型的存储id  |
|writable |boolean   | 是否可写  |

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




