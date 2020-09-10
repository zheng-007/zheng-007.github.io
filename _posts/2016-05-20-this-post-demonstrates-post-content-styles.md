---
layout: page
title: "如何搭建一个个人博客"
date:    2020-09-10 17:30:21 +0086
author: "Bart Simpson"
meta: "Springfield"
---
# 搭建个人技术博

> 使用Github pages + Jekyll 快速部署个人博客

> - Github pages
>    - 给所有的注册用户提供一个个人主页
>    - 如何访问：域名 用户名.github.io
>    - 如何编写主页：建立一个以个人域名为项目名的远程版仓本库，只需要向远程版本库的master分支提交代码就行（该代码中必须有个文件叫index.html）。
> - Jekyll
>    - 定义：可以将markdawn语法自动编译成html的一个工具
>    - 安装：不需要自己安装，在github网站中预安装的
>    - 使用：当你请求个人域名时，github服务器会读取仓库（以个人域名命名的项目名远程版本库）中的master分支中的代码，如果该代码为markdown语法会自动调用Jekyll将其编译为html，并返回客户端。

- 建立一个以个人域名为项目名的远程版本仓库
- 访问网站：一个主题网站 http://Jekyllthemes.org/. 选择一个主题将其代码复制到我们的仓库master分支
- 以上两步可以合并为一步，在主题仓库点击fork，点击setting设置仓库名，即可
- 将远程版本库的代码克隆到本地
    - 点击头像，点code  复制资料
    - 在文件打开终端执行克隆 
       `git clone -b master https://github.com/zheng-007/zheng-007.github.io.git myBlog`
- 修改配置文件以及页面内容
- 书写博客

