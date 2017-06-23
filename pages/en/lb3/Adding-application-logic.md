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

* **[Adding logic to models](Adding-logic-to-models.html)** - adding [remote methods](Remote-methods.html), [remote hooks](Remote-hooks.html) and [operation hooks](Operation-hooks.html).
* **[Defining boot scripts](Defining-boot-scripts.html)** - writing scripts (in the `/server/boot` directory) that run when the application starts.
* **[Defining middleware](Defining-middleware.html)** - adding custom [middleware](http://expressjs.com/api.html#middleware) to the application .
