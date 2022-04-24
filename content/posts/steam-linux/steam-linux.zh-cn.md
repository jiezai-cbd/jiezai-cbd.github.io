---
title: "记录在linux上使用steam"
subtitle: ""
date: 2022-04-24T21:45:29+08:00
draft: false
author: "jiezai-cbd"
authorLink: "jiezai-cbd.xyz"
description: "记录在linux上使用steam"
keywords: ""
license: ""
comment: false
weight: 0

tags: ["steam", "game"]
categories: ["ACGN"]

hiddenFromHomePage: false
hiddenFromSearch: false

summary: ""
resources:
- name: featured-image
  src: featured-image.jpg
- name: featured-image-preview
  src: featured-image-preview.jpg

toc:
  enable: true
math:
  enable: false
lightgallery: false
seo:
  images: []

# See details front matter: /theme-documentation-content/#front-matter
---
test
<!--more-->
steam在linux上可以使用proton运行只支持windows的程序，然而我在使用时发现只有很少一部分游戏可以成功运行，还有很多游戏要么就是无法打开，要么就是打开后闪退，要么就是打开后报错，就连商店里标明的支持linux的游戏也有这种问题，这里记录解决的方式。
参考protondb.com

# 爱上火车:last run(maitetsu:last run!)
> //支持平台 windows
> //打开后闪退,添加一下代码后成功运行，然而游戏只有6帧，不知道为什么
> PROTON_USE_WINED3D11=1 %command%

# doki doki literature clue plus!
> //支持平台 windows
> //打开后报Failed to initialize graphics.,添加一下代码后成功运行，然而游戏里鼠标不显示，不知道为什么
> PROTON_USE_WINED3D11=1 %command%
