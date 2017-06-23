---
title: "Adding application logic"
lang: en
layout: page
keywords: LoopBack
tags: [application_logic]
sidebar: lb3_sidebar
permalink: /doc/en/lb3/Adding-application-logic.html
summary:
---

构建一个应用程序时，你通常需要实现定制的逻辑来处理数据和执行其他操作，以便响应客户端的请求。在LoopBack中，做此事有三种方式：

* **[给模型添加逻辑](Adding-logic-to-models.html)** - 添加 [remote methods](Remote-methods.html), [remote hooks](Remote-hooks.html) 和 [operation hooks](Operation-hooks.html).
* **[定义启动脚本](Defining-boot-scripts.html)** - 编写应用程序启动时运行的脚本 (在 `/server/boot` 目录中)
* **[定义中间件](Defining-middleware.html)** - 给应用程序添加定制的 [中间件](http://expressjs.com/api.html#middleware)
