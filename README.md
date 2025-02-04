# `Linux`网络编程


## 01P 复习`Linux`网络编程

## 02P 信号量生产者复习

## 03P 协议

## 04P 7层模型和4层模型及代表协议

## 05P 网络传输数据封装流程

## 06P 以太网帧和`ARP`请求

## 07P `IP`协议

## 08P 端口号和`udp`协议

## 09P `TCP`协议

## 10P `BS`和`CS`模型比对

## 11P 套接字

## 12P 回顾

## 13P 网络字节序

## 14P `IP`地址转换函数

## 15P `sockaddr`地址结构

## 16P `socket`模型创建流程分析

## 17P `socketubind`

## 18P `listen`和`accept`

## 19P `connect`

## 20P `CS`模型的`TCP`通信分析

## 21P `server`的实现

## 22P 获取客户端地址结构

## 23P `client`的实现

## 24P 总结

## 25P 复习

## 26P 二次握手建立连接

## 27P 数据通信

## 28P 四次握手关闭连接

## 29P 半关闭补充说明

## 30P 错误处理函数的封装思路

## 31P 滑动窗口和`TCP`数据包格式

## 32P 通信时序与代码对应关系

## 33P `TCP`通信时序总结

## 34P 错误处理函数封装

## 35P 封装思想总结和`readn`、`readline`封装思想

## 36P 中午复习

## 37P 多进程并发服务器思路分析

## 38P 多线程并发服务器分析

## 39P 多进程并发服务器实现

## 40P 多进程服务器测试`ip`地址调整

## 41P 服务器程序上传外网服务器，并访问

## 42P 多线程服务器代码`review`

## 43P `read`返回值和总结

## 44P 复习

## 45P `TCP`状态-主动发起连接

## 46P `TCP`状态-主动关闭连接

## 47P `TCP`状态-被动接收连接

## 48P `TCP`状态-被动关闭连接

## 49P `2MSL`时长

## 50P `TCP`状态-其他状态

## 51P 端口复用函数

## 52P 半关闭及`shutdown`函数

## 53P 多路`I0`转接服务器设计思路

## 54P `select`函数参数简介

## 55P 中午复习

## 56P `select`函数原型分析

## 57P `select`相关函数参数分析

## 58P `select`实现多路`I0`转接设计思路

## 59P `select`实现多路`I0`转接-代码`review`

## 60P `select`现多路`I0`转接-代码实现

## 61P `select`实现多路`I0`转接-添加注释

## 62P `select`优缺点

## 63P 添加一个自己定义数组提高效率

## 64P 总结

## 65P 复习

## 66P `poll`函数原型分析

## 67P `poll`函数使用注意事项示例

## 68P `poll`函数实现服务器

## 69P `poll`总结

## 70P `epoll`函数实现的多路`IO`转接

## 71P 突破1024文件描述符设置

## 72P `opell`、`create`和`epoll ctl`

## 73P `epoll` `wait`函数

## 74P 中午复习

## 75P `ET`和`LT`模式

## 76P 网络中`ET`和`LT`模式

## 77P `epol`的`ET`非阻塞模式

## 78P `epoll`优缺点总结

## 79P 补充对比`ET`和`LT`

## 80P `epol`反应堆模型总述

## 81P `epoll`反应堆`main`逻辑

## 82P `epoll`反应堆-给`lfd`和`cfd`指定回调函数


## 83P `epoll`反应堆-`initlistensocket`小总结

## 84P `epoll`反应堆-`wait`被触发后`read`和`write`回调及监听

## 85P `epoll`反应堆-超时时间

## 86P 总结

## 87P 复习

## 88P 补充说明`EPOLL`的`man`手册

## 89P `epoll`反应堆再说明

## 90P `ctags`使用

## 91P 线程池模型原理分析

## 92P 线程池描述结构体

## 93P 线程池`main`架构

## 94P 线程池-`pthreadpool create`

## 95P 子线程回调函数

## 96P 管理者线程

## 97P `threadpool add`函数

## 98P 条件满足，子线程`wait`被唤醒后处理任务

## 99P 线程池扩容和销毁

## 100P `TCP`和`UDP`通信优缺点

## 101P `Udp`通信`server`和`cient`流程

## 102P `recvfrom`和`sendto`函数

## 103P `upd`实现的并发服务器和客户端

## 104P 借助`TCP`的`CS`模型，改写`UDP`的`CS`模型

## 105P 本地套接字和网络套接字比较

## 106P 本地套接字通信

## 107P 本地套接字和网络套接字实现对比

## 108P 总结

## 109P 复习

## 110P `ibevent`简介


## 111P `libevent`库的下载及安装

## 112P `libevent`封装的框架思想

## 113P 结合`helloworld`初识`libevent`

## 114P 框架相关的不常用函数

## 115P 创建事件对象`event`

## 116P 事件`event`操作

## 117P 使用`ffo`的读写

## 118P 使用`ffo`的读写编码实现

## 119P 未决和非未决

## 120P 中午复习

## 121P `bufferevent`特性

## 122P `bufferevent`事件对象创建、销毁

## 123P 给`bufferevent`事件对象设置回调

## 124P 缓冲区开启和关闭

## 125P 客户端和服务器连接和监听

## 126P `ibevent`实现`Tcp`服务器流程

## 127P `ibevent`实现`TCp`服务器源码分析

## 128P 服务器注意事项

## 129P 客户端流程简析和回顾

## 130P 总结

## 131P 复习

## 132P `web`大练习的概述

## 133P `html`文本和标题

## 134P 错误页面`html`

## 135P 列表、图片和超链接

## 136P `http`协议请求、应答协议基础格式

## 137P 服务器框架复习和`getline`函数

## 138P 复习

## 139P 单文件通信流程分析

## 140P 处理出错返回

## 141P 正则表达式获取文件名

## 142P 判断文件是否存在

## 143P 写出`http`应答协议头

## 144P 写数据给浏览器

## 145P 文件类型区分

## 146P 错误原因说明

## 147P 错误页面展示

## 148P 关于浏览器请求`ico`文件

## 149P 浏览器请求目录

## 150P 判断文件类型

## 151P 汉字字符编码和解码

## 152P `libevent`实现的`web`服务器

## 153P `telnet`调试