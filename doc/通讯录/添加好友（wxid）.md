

[TOC]
    
##### 简要描述

- 通过wxid添加好友，只能添加有交集的人（以前是好友或在同一个群聊）

##### 请求URL
- ` http://127.0.0.1:8888/api/`
  
##### 请求方式
- POST 

##### 参数

|参数名|必选|类型|说明|
|:----    |:---|:----- |-----   |
|type |是  |int | 接口编号    |
|userName |是  |string | wxid    |
|message |否  |string | 验证信息    |

##### 请求示例

```
 {
  "type": 10034,
  "userName": "wxid_xxxx",
  "message": "我是xxx",
 } 
```

##### 返回示例 

``` 
  {
    "error_code": 10000,
    "description": "",
    "data": {
      "status": 0,
      "desc": "",
    }
  }
```

##### 返回参数说明 

|参数名|类型|说明|
|:-----  |:-----|-----                           |
|error_code |int   |错误代码  |
|description|string|错误描述|
|data|json|业务数据|

##### 备注 

- 更多返回错误代码请看首页的错误代码描述






