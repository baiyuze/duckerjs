# Duckerjs

## 一、功能列表

## 基础功能

* 基于koa-router进行重写router
* 日志功能
* config配置管理
* 环境变量管理
* http请求管理

## 增强功能

### 中间件功能
#### 基于koa2的剥洋葱模型
![](https://camo.githubusercontent.com/d80cf3b511ef4898bcde9a464de491fa15a50d06/68747470733a2f2f7261772e6769746875622e636f6d2f66656e676d6b322f6b6f612d67756964652f6d61737465722f6f6e696f6e2e706e67)

#### 中间件执行顺序图：

![](https://raw.githubusercontent.com/koajs/koa/a7b6ed0529a58112bac4171e4729b8760a34ab8b/docs/middleware.gif)

#### 适配[Koa2](https://koa.bootcss.com/)的所有中间件

### 插件功能
* 每个插件都有自己独立的配置
* 和主系统互不影响

### 进程守护
* 开发进程守护
* 生产进程守护

### 进程机制（cluster）
* 主进程 master
* 辅助进程 Agent
* 工作进程 worker


## 二、完成顺序

#### duckerjs-bin

> 开发工具

#### duckerjs-core

> duckerjs核心代码

#### duckerjs-router

> 路由router，路由定制扩展

#### duckerjs-logger

> 日志功能自定义

#### duckerjs-cluster

> 启动进程