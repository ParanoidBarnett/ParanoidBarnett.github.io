---
title: Win10 激活
date: 2019-12-12 07:46:55
tags: [其他,系统]
categories: [win10]
---
4行命令激活，适用于Windows10正式专业版，来自网友的智慧，2019年11月重装系统1903版本验证有效。
## 操作步骤

### 首先“以管理员身份”运行命令行提示符工具

在“cortana”搜索框中输入“CMD”，待出现“命令提示符”工具时，右击选择“以管理员身份”运行。

### 输入

``` bash
slmgr.vbs /upk
```
回车执行后弹出窗口显示“已成功卸载了产品密钥”。

### 输入

``` bash
slmgr /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX
```
回车执行后弹出窗口显示“成功的安装了产品密钥”。

### 输入

``` bash
slmgr /skms zh.us.to
```
回车执行后弹出窗口显示“密钥管理服务计算机名成功的设置为 zh.us.to”。

### 输入

``` bash
slmgr /ato
```
回车执行后弹出窗口显示“成功的激活了产品”。

### 结束