---
layout: post
title:  新浪微博的OAuth2认证过程
date:   2016-07-14 13:31:01 +0800
categories: jekyll
tag: jekyll
---

* content
{:toc}


# Hello World

以上就是如何使用浏览器模拟微博的oauth2认证过程，省去使用sdk，可以直接用
在我们的应用中，但是，有一个小问题我想不明白，第二步获取的code必须是通过
回调uri的参数处获得，不知道各sdk里是如何获取到这个code的？
