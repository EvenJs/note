# Express  
req.body  
req.params  
req.query  
req.cookies  

>app.method(path,handler)
- app 是一个express服务器对象  
- method 可以是任何小写的HTTP请求方法(get,post,put,delete)  
- path 是客户端访问的URI，例如 / 或 /about    
- handler 是路由被触发时的回调函数，在函数中可以执行相应业务逻辑

### Router


### Middleware 
具体业务逻辑和底层逻辑解耦的组件
- 中间件是按顺序执行的，配置中间件时顺序非常重要
- 中间件在执行内部逻辑的时候可以选择将请求传递给下一个中间，也可以直接返回用户响应

