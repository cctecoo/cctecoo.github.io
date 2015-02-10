title: hexo博客搭建
date: 2015-01-13 13:15:19
categories: Hexo
tags: [hexo,]
--- 
##什么是hexo
> A fast, simple & powerful blog framework, powered by Node.js.

hexo是一个基于Node.js的静态博客程序，可以方便的生成静态网页托管在github上。
以下简单介绍hexo搭建博客的过程

<!--more-->

##Linux ubuntu
install git
install node.js
*每次*nvm use 0.10.35(node.js版本号)
npm install -g hexo
cd到你的博客文件目录 hexo init初始化
npm install    //安装依赖包(public里文件是hexo要发布)

Enjoy writing blog!

####**Hexo 常用命令**
```python
hexo new
hexo generate
hexo server
hexo develop
hexo clean
```