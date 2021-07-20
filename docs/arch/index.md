---
hide:
  - navigation
  #- toc
---

### 技术栈

- JAVA 8
- PostgreSQL12 , 兼容MySQL5.7
- Gradle
- Docker Compose 一键部署
- AngularJS


### 多店铺防关联

善知鸟分为三个部分

|模块     |说明                      |部署限制|
| ----------- | ----------- | ------------------------------------ |
|`Amazon API Worker`|调用店铺API,获取订单/Listing/库存报告数据|和店铺部署在同一台机器上,有多少店铺部署多少个|
|数据库|存储您的ERP全部数据|您办公室某台电脑或者云计算|
|善知鸟程序      |ERP主体程序|您办公室某台电脑或者云计算|

### 部署环境要求

- 首选Linux/CentOS7.x
- 苹果Mac任意版本
- Window 10
- Window 10以下版本能部署,但是部署运维很麻烦