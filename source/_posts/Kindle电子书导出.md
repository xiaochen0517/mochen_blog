---
title: Kindle电子书导出
date: 2022-02-18 13:53:08
tags:
  - 日常技巧
  - 电子书
  - Kindle
categories: 
  - 其他
  - 杂项
---


原版 `Kindle for pc` 软件是不支持修改字体、滚动阅读等很多设置，自带的背景色也是没有合适的颜色，体验十分差劲。好在有许多第三方的阅读器，但是 `Kindle` 下载的电子书是加密的，这篇文章就是如何破解电子书并导入第三方工具进行阅读的教程。

<!-- more -->

## 下载工具

calibre 下载地址：https://calibre-ebook.com/download_windows

Kindle for pc 下载地址：https://www.amazon.cn/b/ref=sv_kinc_0?ie=UTF8&node=2331640071

DeDRM_tool 插件：https://github.com/apprenticeharper/DeDRM_tools/releases

## 下载电子书

首先安装 Kindle for pc 并登录，选择图书下载。点击菜单栏 `工具->选项` 后打开内容栏，查看图书保存位置，并在资源管理器中打开。

{% asset_img 01.png 工具选项内容 %}

打开资源管理器

{% asset_img 02.png 资源管理器 %}

注意上面两个名字类似的文件夹，这就是下载完成的电子书储存的目录，该目录下的 `azw` 文件即是加密的电子书。

## 开始破解

将文件夹中的 `azw` 文件复制一份移到其他文件夹，打开 `calibre` 软件，开始下载插件。

首先点击首选项按钮：

{% asset_img 04.png 资源管理器 %}

再点击插件按钮：

{% asset_img 05.png 资源管理器 %}

点击获取新的插件：

{% asset_img 06.png 资源管理器 %}

搜索 `KFX` 下载安装下面插件即可：

{% asset_img 03.png 资源管理器 %}


解压下载好的 `DeDRM_tools_x.x.x.zip` ，其中有名为 `DeDRM_tools.zip` 的文件，这个才是需要安装的插件，再次打开插件页面。

{% asset_img 06.png 资源管理器 %}

点击右下角，从文件加载插件，选中刚才解压的插件。

打开 `calibre` 后进入插件页面，选中 `仅显示用户自己安装的插件` 打开文件类型栏，即可看到刚刚安装的 `DeDRM` 插件，选中插件后点击下方的 `自定义插件` 。

{% asset_img 07.png image %}

点击最后一个 `Kindle for Mac/PC ebooks` 选项，注意，在执行此操作时 `Kindle for pc` 必须已经处于登录状态，否则无法正常认证。

{% asset_img 08.png image %}

点击右侧第一个加号按钮会弹出对话框，让输入 `key` 的名称，直接默认 `default_key` 就好。

> 注意：此操作可能会有较大延迟，点击一次加号后就等待弹窗即可，不要多次点击。

完成此操作后，直接关闭、确定、应用依次点击即可，最后导入复制的 `azw` 文件（首页第一个添加书籍按钮，或者直接将文件拖到窗口中即可）。双击查看，就可以直接查看 `azw` 文件了。

{% asset_img 09.png image %}

## 转换

选中导入的电子书，再点击工具栏中的 `转换书籍` 按钮，所有都可以为默认直接点击 `确定` 按钮，即可导出 `epub` 文件。转换完成后直接右键电子书，点击 `打开所在目录` 即可。

## 结尾

推荐使用 `Neat Reader` 有云同步功能，会员也不贵功能完整，主要是可以调节字体和滚动查看了。

{% asset_img 10.png image %}