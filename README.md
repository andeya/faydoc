# Faygo User Manual

User manual of faygo frame.

[Faygo](https://github.com/henrylee2cn/faygo) uses the new architecture to make itself the most suitable Go Web framework for developping API. Just define a struct Handler, Faygo will automatically bind, verify the request parameters and generate the online API documentation.

[简体中文](README_ZH.md)

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
