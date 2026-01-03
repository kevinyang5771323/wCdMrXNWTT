# 基于Spring Boot+Vue的课堂管理系统 java427

## 项目概述

本项目是一个课堂管理系统，采用前后端分离的架构设计，前端使用Vue.js构建，后端基于Spring Boot框架，提供了一系列便于教师授课管理以及学生选退课的功能模块。

## 技术栈

- 后端：Spring Boot、MyBatis、Redis、WebSocket
- 前端：Vue CLI、Axios、Element UI

## 功能模块

### 课程管理模块

- 教师端：支持添加、编辑、删除课程
- 学生端：支持选课、退课

### 聊天室

- 在线用户列表显示
- 实时聊天功能

### 签到

- 教师端发起课程签到
- 学生端完成签到，状态实时更新

### 笔记管理

- 浏览公开笔记
- 使用Markdown语法添加和编辑笔记

## 系统角色

- 教师：负责课程管理、发起签到、查看签到情况、管理笔记
- 学生：参与选课、退课、签到、查看及编辑笔记

## 运行环境

- 后端：Java 1.8+，MySQL 5.7+，Redis，支持Spring Boot的后端服务器
- 前端：Node.js，支持Vue.js的前端服务器

## 部署步骤

具体部署步骤请参考以下目录结构的对应项目中的`README.md`文件。

## 目录结构

```
project
├── classroom-manager                # 后端项目
└── classroom-manager-front          # 前端项目
```

## 核心亮点

- 高效的后端服务：采用MyBatis连接数据库，提供快速稳定的后台服务。
- 数据缓存：使用Redis缓存签到记录，提高系统响应速度。
- 界面布局与设计：前端采用Element UI，界面美观且易于使用。
- 跨域请求：通过配置代理服务器，使用Axios解决跨域问题。
- 状态管理：利用js-cookie存储用户登录状态，保障系统安全。

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)


## 项目截图

![](https://img14.360buyimg.com/ddimg/jfs/t1/331532/11/17298/26580/68d4dbddFa5dcc063/232ae6d5994c19f2.jpg)

![](https://img14.360buyimg.com/ddimg/jfs/t1/323910/23/23818/26563/68d4dbddFa867a4ab/fbc6d0ef7c4713de.jpg)

![](https://img10.360buyimg.com/ddimg/jfs/t1/343515/39/6837/25607/68d4dbddF036852e9/478d3ae1c3567088.jpg)

![](https://img14.360buyimg.com/ddimg/jfs/t1/324537/20/23702/28079/68d4dbddF2505af95/ae6699baa2e2567b.jpg)

![](https://img11.360buyimg.com/ddimg/jfs/t1/334985/31/17093/30684/68d4dbdeF88e2d066/51877b94e68e37cd.jpg)

![](https://img11.360buyimg.com/ddimg/jfs/t1/85610/10/46097/26536/68d4dbdeFab135f1a/9314b0217a0bf78d.jpg)

![](https://img11.360buyimg.com/ddimg/jfs/t1/324822/35/23638/38547/68d4dbdfFd313a706/73e5a8102dfff5f4.jpg)

