
## 请求URL
- `http://localhost:9887/api/admin/storage`

## 请求方式
- GET

## 返回示例

``` 
{
    "code": 0, 
    "msg": null, 
    "data": [
        {
            "id": 2848000, 
            "name": "主存储", 
            "description": "", 
            "workType": "MAIN", 
            "refStorageType": "GITEE", 
            "refStorageId": 2847568, 
            "refStorageName": "Gitee 主存储", 
            "mainStorageId": null, 
            "mainStorageName": null, 
            "writable": true, 
            "createdDate": "2020-12-26 23:56:03", 
            "lastModifiedDate": "2021-04-11 03:50:08"
        }, 
        {
            "id": 146535952, 
            "name": "备份", 
            "description": "etesfw", 
            "workType": "BACKUP", 
            "refStorageType": "GITHUB", 
            "refStorageId": 148060048, 
            "refStorageName": "github备份", 
            "mainStorageId": 2848000, 
            "mainStorageName": "主存储",
            "writable": true, 
            "createdDate": "2021-04-09 22:31:00", 
            "lastModifiedDate": "2021-04-11 00:58:53"
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
|workType |string   | 工作类型，MAIN-主节点，BACKUP-备份  |
|refStorageType |string   | 管理的存储类型，有 GITHUB，GITEE,LOCAL  |
|refStorageId |int   | 管理的存储id  |
|refStorageName |string   | 关联的存储名字  |
|mainStorageId |int   | 主存储id，workType=BACKUP 才会有  |
|mainStorageName |string   | 主存储名称，workType=BACKUP 才会有  |
|writable |boolean   | 是否可写  |
|createdDate |string   | 创建时间  |
|lastModifiedDate |string   | 修改时间  |




