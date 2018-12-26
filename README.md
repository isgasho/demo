demo用于演示这个base业务框架的使用，方便大家对它更加熟悉

demo由三个微服务构成：gateway、token和user


1. gateway作为网关，对外提供web服务
2. token对已登录用户进行身份验证
3. user获取用户相关信息。

## gateway

gateway作为网关，所有的外部流量都经过它

## token

token作为用户唯一身份

## user

用户服务

## DEMO截图

### 配置中心

![查询地址接口](https://gewuwei.oss-cn-shanghai.aliyuncs.com/tracelearning/WechatIMG48.jpeg)

### 查询接口

1. 查询me接口

![查询me接口](https://gewuwei.oss-cn-shanghai.aliyuncs.com/tracelearning/WechatIMG44.jpeg)

2. 查询错误码接口

![查询错误码接口](https://gewuwei.oss-cn-shanghai.aliyuncs.com/tracelearning/WechatIMG45.jpeg)

3. 查询地址接口

![查询地址接口](https://gewuwei.oss-cn-shanghai.aliyuncs.com/tracelearning/WechatIMG46.jpeg)

4. 日志目录结构与日志信息截图

![查询地址接口](https://gewuwei.oss-cn-shanghai.aliyuncs.com/tracelearning/WechatIMG47.jpeg)

5. mysql截图

![查询地址接口](https://gewuwei.oss-cn-shanghai.aliyuncs.com/tracelearning/WechatIMG49.jpeg)

## 演示环境


### 服务列表

| 服务名 | 服务地址 | 用户名 | 密码 |
|---|---|---|---|
| zkui | [zkui](http://39.96.95.220:9090/login) | admin | manager |
| gateway | [demo-dev](http://39.96.95.220:8081) | - | - |
| token | 192.168.0.79:8084 | - | - |
| user | 192.168.0.79:8085 | - | -|
