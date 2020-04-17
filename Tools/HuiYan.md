# 慧眼

## 介绍

## 基本原理

基于App的dex文件，通过解析dex文件并根据App的生命周期建立函数调用模型，使用静态数据流分析的方法，静态模拟代码数据的传播，实现静态数据的跟踪以达到精准定位漏洞的目的。

慧眼从以下方面对App进行检测：

* Network
* Binary
* Configuration,
* ICC
* Cryto
* System
* Webview
* Storage

## 常规漏洞检测项

### 组件间通信

* Intent Bridge 组件权限泄露
* Content Provider 路径穿越漏洞
* 隐式Intent数据泄露

### 存储

* SQL 注入风险
* Intent 调用路径穿越
* SQLite 数据库全局可读写
* 文件全局可读写

### 网络通信

* Socket 端口
* 证书弱校验
* 主机名弱校验
* Webview 密码明文存储

### 加密

* RSA 私钥硬编码
* RSA 弱密钥
* 加密模式使用错误风险
* 固定初始化
* 固定盐风险
* 密码硬编码

### 第三方SDK

* 第三方SDK漏洞

### Javascript Interface

* 命令行
* 解压缩路径穿越
* 不安全插件加载
* Native 库安全编译风险

### 其他检测

* ExportedComponent 
* WorldReadable
* RuntimeExec
* ECBCrytoConfig

