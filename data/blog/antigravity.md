---
title: 解决 Google Antigravity 无法登陆的问题
type: Blog
date: 2025-11-20
tags: [笔记, 教程]
keywords: [ifcat, Google Antigravity, Antigravity]
draft: false
description: Google Antigravity 登陆时遇到两个问题，一个是登陆时浏览器回跳Antigravity后没有反应，一个是有反应后报错 "your current account is not eligible for antigravity, because it is not currently available in your location."
summary: Google Antigravity登陆时遇到两个问题，一个是登陆时浏览器回跳Antigravity后没有反应，一个是有反应后报错 "your current account is not eligible for antigravity, because it is not currently available in your location."
---
## 前言

&emsp;&emsp;Google Antigravity登陆时遇到两个问题，一个是登陆时浏览器回跳Antigravity后没有反应，一个是有反应后报错:``your current account is not eligible for antigravity, because it is not currently available in your location.``。

<TOCInline toc={props.toc} exclude="Overview" toHeading={3} />

## 问题1：浏览器回跳Antigravity后没有反应

&emsp;&emsp;以**TUN**的模式开启代理即可，也就是虚拟网卡模式。
![image.png](https://cdn.jsdelivr.net/gh/h-yw/note-gen-image-sync@master/414ca6a6-d28d-4a33-aea1-8b440cd3c8d5.png)

## 问题2：``your current account is not eligible for antigravity, because it is not currently available in your location.``

&emsp;&emsp; 显然是区域问题，需要修改 google 账号的关联区域。去 [**https://policies.google.com/country-association-form**](https://policies.google.com/country-association-form) 修改账号关联区域，切换到支持Antigravity的区域即可。不过这个需要google审核，大概几十分钟后就能收到邮件。

![image.png](https://cdn.jsdelivr.net/gh/h-yw/note-gen-image-sync@master/2e859ec5-15a5-431c-9345-e8d6657f64da.png)
