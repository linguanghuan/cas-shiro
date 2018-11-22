# cas shiro pac4j 客户端

## 版本
```
    cas服务端: 4.0.0
    springboot: 2.0.6.RELEASE
```

## 运行
### 配置hosts映射
```
127.0.0.1       app1
127.0.0.1       app2
```

### 启动参数
```
app1: --spring.profiles.active=app1
app2: --spring.profiles.active=app2
```

### 运行地址
```
cas服务端: http://localhost:8080/cas/
app1: http://app1:8082
app2: http://app2:8083
```

## 参考
1. [spring boot 2.0 集成 shiro 和 pac4j cas单点登录](http://www.cnblogs.com/suiyueqiannian/p/9359597.html)
2. [cas-4.0.0-server 简单部署](https://blog.csdn.net/c1481118216/article/details/80396851)
3. [cas-4.0.0-server 去掉https验证](https://blog.csdn.net/c1481118216/article/details/80397284)
4. [cas-4.0.0 客户端配置](https://blog.csdn.net/c1481118216/article/details/80411369)
5. [cas-4.0.0-server 配置mysql数据库查询认证](https://blog.csdn.net/c1481118216/article/details/80402622)

