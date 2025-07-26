---
title: '宝塔面板安装 WordPress 详细教程：从零开始搭建网站'
description: '详细介绍如何使用宝塔面板快速安装 WordPress，包括环境配置、数据库创建、域名绑定等完整建站流程。适合新手站长的宝塔 WordPress 搭建指南。'
cover: ''
date: 2025-07-26 18:07:05
categories:
  - 建站教程
  - 服务器运维
tags:
  - 宝塔面板
  - WordPress
  - 建站
  - 网站搭建
  - 服务器管理
  - LAMP
  - LNMP
  - 域名绑定
---

## 环境准备

确保安装了 Nginx、MySQL、PHP 环境。

![](https://cdn.jsdelivr.net/gh/youngjuning/images@main/1753541490034.png)

## 新建站点

进入宝塔面板，点击左侧的“网站”，然后点击“添加站点”。

![](https://cdn.jsdelivr.net/gh/youngjuning/images@main/1753542436855.png)

点击 “一键部署”，选择 WordPress 模版，输入域名。建议 www 和非 www 都部署。

![](https://cdn.jsdelivr.net/gh/youngjuning/images@main/1753542516497.png)

## SSL 证书

网站部署完成后，点击 “SSL”，选择 “Let's Encrypt”，点击 “提交”。

![](https://cdn.jsdelivr.net/gh/youngjuning/images@main/1753542750792.png)

记得勾选 “强制 HTTPS” 和到期提醒。

![](https://cdn.jsdelivr.net/gh/youngjuning/images@main/1753542996550.png)

## 伪静态

选择 wordpress 模版，点击 “提交”。

![](https://cdn.jsdelivr.net/gh/youngjuning/images@main/1753543586057.png)

## 301 重定向

重定向设置，选择 “301 重定向”，点击 “提交”。

![](https://cdn.jsdelivr.net/gh/youngjuning/images@main/1753543929126.png)
