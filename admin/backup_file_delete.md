
## 请求URL
- `http://localhost:9887/api/admin/backup/{fileName}`

## 请求方式
- DELETE

## 参数

请求地址中的 {fileName} 是参数

|参数名|必选|类型|说明|
|:----    |:---|:----- |-----   |
|fileName  |是  |string |文件名   |


## 返回示例

``` json
{
    "code": 0, 
    "msg": "登录成功"
}
```

## 返回参数说明

|参数名|类型|说明|
|:-----  |:-----|-----                           |
|code |int   |返回码，0-正常，1-异常  |
|msg |string   | 返回消息  |

