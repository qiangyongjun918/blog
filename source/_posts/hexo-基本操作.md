---
title: hexo 基本操作
date: 2020-03-08 16:59:41
tags: [hexo]
categories: [hexo, ]
---
Hexo 框架可以帮助我们快速创建一个属于自己的博客网站，熟悉 Hexo 框架提供的命令有利于我们管理博客

<!-- more -->

## Quick Start

### Create a new blog

``` bash
$ hexo init "folder"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Create a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/one-command-deployment.html)

### server to combination

``` bash
$ hexo clean && hexo s --debug -p 5555
```

More info: [Deployment](https://hexo.io/docs/one-command-deployment.html)

### Deploy to combination

``` bash
$ npm install hexo-deployer-git  --save
$ hexo clean && hexo g && hexo d
```

More info: [Deployment](https://hexo.io/docs/one-command-deployment.html)
