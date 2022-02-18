---
title: OpenJDK源码下载-包括CPP文件
date: 2022-02-13 12:25:07
tags: 
  - JDK
  - 资源下载
categories: 资源下载
---

在 `Oracle` 中下载的 `JDK` 中是不包含 `CPP` 源码的，需要下载 `OpenJDK` 源码进行查看。

```
https://download.java.net/openjdk/jdk8/
```

若需要 `JDK7` 只需将 `jdk8` 修改为 `jdk7` 即可。

{% asset_img 01.png This is an image %}


此处即为源码包的下载链接，但是点开后发现无法下载。点击 `f12` 找到此 `a` 标签的路径，发现链接应该是 `downlaod.*` 变成了 `www.*` 。

{% asset_img 02.png This is an image %}

将链接 `www.java.net/download/openjdk/` 的部分修改为 `download.java.net/openjdk/` 即可下载。

下载速度过慢可以使用**迅雷**加速。

下载完成后使用 `vscode` 以项目打开即可查看 `CPP` 源码。

{% asset_img 03.png This is an image %}