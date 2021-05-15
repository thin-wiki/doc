
## 请求URL
- `http://localhost:9887/api/admin/backup`

## 请求方式
- GET

## 返回示例

``` 
{
    "code": 0, 
    "msg": null, 
    "data": [
        {
            "fileName": "2021_04_17_16_38_53.sql.zip", 
            "length": 152730, 
            "lastModified": "2021-04-17 16:38:53"
        }, 
        {
            "fileName": "2021_04_17_16_37_51.sql.zip", 
            "length": 152713, 
            "lastModified": "2021-04-17 16:37:52"
        }
    ]
}
```

## 返回参数说明

|参数名|类型|说明|
|:-----  |:-----|-----                           |
|code |int   |返回码，0-正常，1-异常  |
|msg |string   | 返回消息  |
|fileName |string   | 文件名  |
|length |int   | 文件大小，单位是 B，可以适当转为 kb，mb，gb等  |
|lastModified |string   | 最后修改时间  |




