# Faygo用户手册

[Faygo](https://github.com/henrylee2cn/faygo) 使用全新架构，是最合适开发API接口的Go Web框架。用户只需定义一个struct Handler，就能自动绑定、验证请求参数并生成在线API文档。

官方QQ群：Go-Web 编程 42730308    [![Go-Web 编程群](http://pub.idqqimg.com/wpa/images/group.png)](http://jq.qq.com/?_wv=1027&k=fzi4p1)

文档状态：完善中...

## 目录

* 1.[欢迎使用 faygo](zh/01.00.md)
 - 1.1. [安装 faygo](zh/01.01.md)
 - 1.2. [项目架构](zh/01.02.md)

* 2.[创建服务](zh/02.00.md)
 - 2.1. [单服务&单监听](zh/02.01.md)
 - 2.2. [单服务&多监听](zh/02.02.md)
 - 2.3. [多服务&单监听](zh/02.03.md)
 - 2.4. [多服务&多监听](zh/02.04.md)

* 3.[项目部署运行](zh/03.00.md)
 - 3.1. [启动所有服务实例](zh/03.01.md)
 - 3.2. [平滑关闭与重启](zh/03.02.md)
 - 3.3. [部署及元编程工具 fay](zh/03.03.md)

* 4.[操作与中间件](zh/04.00.md)
 - 4.1. [函数类型Handler](zh/04.01.md)
 - 4.2. [结构体类型Handler](zh/04.02.md)
 - 4.3. [Swagger2.0在线API文档](zh/04.03.md)

* 5.[路由器](zh/05.00.md)
 - 5.1. [两种注册形式](zh/05.01.md)
 - 5.2. [静态路由](zh/05.02.md)
 - 5.3. [中间件](zh/05.03.md)
 - 5.4. [过滤器](zh/05.04.md)
