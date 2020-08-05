# 个人技术报告
*17343101 苏祺达*

---

## 本人在团队中承担的职责
接口设计，前端项目开发，项目测试，持续集成管理。

## 选用的第三方依赖

* vue：搭建框架，编写组件
* vue-cli: 命令行工具
* vuex：状态管理
* vue-router：前端路由管理
* axios：封装 ajax 请求
* vue-awesome：图标库
* mocker-api：模拟服务端处理数据请求
* eslint：代码风格检查
* mocha：单元测试框架
* cypress：集成测试框架

## 开发过程中遇到的问题

* vue-cli 提供的 e2e 测试命令不会自行结束测试进程，因此改为使用 cypress 提供的 github workflow 配置。
* muse-ui 作为组件库的备选方案长期没有得到维护，于是改为自己实现组件和插件。