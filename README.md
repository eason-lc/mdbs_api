# mdbs_api
# 门店帮手
   >该接口处于开发阶段,采用https协议,接口版本v2
   
## Api接口地址
- 测试环境：https://www.jybd.cn
- 开发环境：https://www.jybd.cn
[锚点][anchor]
[anchor]:#url-more "anchor alt text"
## 标准请求
    curl -X POST|GET
    https://www.jybd.cn/<资源路径> /v2/
## 返回值

Code| 说明  |备注
--- | ---   | --- 
200 | 成功
100 | 请求错误
101 | 缺少appKey
102 | 缺少签名
103 | 缺少参数
200 | 成功
201 | 服务器出错
202 | 服务不可用


## 功能路径列表
资源名称| 路径  |Content-Type| 请求方式 | 维护人 | 是否需要登录
---     | ---   | ---  | --- | --- | --- 
登录    | [login](#index) |json/text   |GET   |杨延伟    |否

## 返回值

Code| 说明  |备注
--- | ---   | --- 
200 | 成功
100 | 请求错误
101 | 缺少appKey
102 | 缺少签名
103 | 缺少参数
200 | 成功
201 | 服务器出错
202 | 服务不可用

## 返回值

Code| 说明  |备注
--- | ---   | --- 
200 | 成功
100 | 请求错误
101 | 缺少appKey
102 | 缺少签名
103 | 缺少参数
200 | 成功
201 | 服务器出错
202 | 服务不可用


<span id = "index">跳转到这里：</span>
[锚点](#url-more "anchor alt text")


### **1.登录**
 
 
 请求
 
    username:用户名
    passwork:密码
    
    

  
