---
layout: default
title: 深链
nav_order: 2
has_children: true
---

# 什么是深链？

在 Android 中，深层链接是指将用户直接转到应用内特定目的地的链接。 -google

无缝链接到您的应用程序或网站上的内容。借助通用链接，您始终可以为用户提供最完整的移动体验，即使您的应用程序未安装在他们的设备上也是如此。
-apple

目的提供外部调用APP方式

----

## 如何接入?

App提供不同平台'深链'实现，表现存在稍微不一致

### android

| 协议    | 地址                             | 例子                                     | 版本    |
|-------|--------------------------------|----------------------------------------|-------|
| bfban | app                            | bfban://app                            | 0.2.3 |
| https | bfban.gametools.network/player | https://bfban.gametools.network/player |  0.2.3     |

### ios or macos

| 协议    | 地址                             | 例子                                     | 版本    |
|-------|--------------------------------|----------------------------------------|-------|
| bfban | app                            | bfban://app                            | 0.2.3 |


----

## 规则

ps: 实际就是get参数 :D

### 打开案例详情

| 参数 | 值   | 类型 | 描述 | 版本 |
|----|-----|-----|----|-----|
| type | player   | String | |0.2.3 |
| id | /   | String | |0.2.3 |

例子: bfban://app?type=player&id=1000

### 打开展示页

| 参数 | 值       | 类型 | 描述 | 版本 |
|----|---------|-----|----|-----|
| type | account | String | |0.2.3 |
| id | /       | String | |0.2.3 |

例子: bfban://app?type=account&id=1000

