
## 请求URL
- `http://localhost:9887/api/admin/storage/local`

## 请求方式
- GET

## 返回示例

``` 
{
    "code": 0, 
    "msg": null, 
    "data": [
        {
            "id": 146509152, 
            "name": "本地主", 
            "description": "本地主", 
            "basePath": "/Users/beldon/Documents/work/me/thin-wiki/data", 
            "createdDate": "2021-04-09 22:03:05", 
            "lastModifiedDate": "2021-04-11 01:02:15"
        }, 
        {
            "id": 148225312, 
            "name": "本地备份", 
            "description": "本地备份", 
            "basePath": "/Users/beldon/Documents/work/me/thin-wiki/data/bk", 
            "createdDate": "2021-04-11 03:50:45", 
            "lastModifiedDate": "2021-04-11 03:50:45"
        }
    ]
}
```

## 返回参数说明

|参数名|类型|说明|
|:-----  |:-----|-----                           |
|code |int   |返回码，0-正常，1-异常  |
|msg |string   | 返回消息  |
|id |int   | id  |
|name |string   | 名字  |
|description |string   | 描述  |
|basePath |string   | 仓库中的文件基本目录  |
|createdDate |string   | 创建时间  |
|lastModifiedDate |string   | 修改时间  |




