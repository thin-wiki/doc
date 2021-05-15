
## 请求URL
- `http://localhost:9887/api/admin/storage/gitee`

## 请求方式
- GET

## 返回示例

``` 
{
    "code": 0, 
    "msg": null, 
    "data": [
        {
            "id": 2847568, 
            "name": "Gitee 主存储", 
            "description": "Gitee 主存储", 
            "token": "xxx", 
            "owner": "thin-wiki", 
            "repo": "static", 
            "branch": "master", 
            "basePath": "files", 
            "createdDate": "2020-12-26 23:55:36", 
            "lastModifiedDate": "2020-12-26 23:55:36"
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
|token |string   | Token  |
|owner |string   | 仓库 Owner  |
|repo |string   | 仓库  |
|branch |string   | 分支  |
|basePath |string   | 仓库中的文件基本目录  |
|createdDate |string   | 创建时间  |
|lastModifiedDate |string   | 修改时间  |




