---
layout:     post
title:      "新的博客成立 2019"
subtitle:   " \"Hello, New Blog\""
date:       2019-11-05 12:00:00
author:     "ZhangNian"
header-img: "img/post-bg-2015.jpg"
catalog: true
tags:
    - 生活
    - Meta
---

> “Yeah It's on. ”

## Start

ZhangNian 的Speech Blog 准备开通了。

[跳过废话，直接看技术实现](#build)

2019 年，ZhangNian 总算有个地方可以好好写点东西了。

作为一个程序员， Blog 这种轮子要是挂在大众博客程序上就太没意思了。一是觉得大部分 Blog 服务都太丑，二是觉得不能随便定制不好玩。之前在CSDN上写过一段时间的博客， 但是广告之类的东西看着让人真是心烦，下决心搞个新的博客。

在学习语音识别相关知识后，打算把自己知道的一些东西写下来和大家共享，这里主要记录语音识别和语音合成相关知识，本人工作时间不长，如果有错误的地方可以发私信，请大家见谅,希望大家可以一起成长!

<p id="build"></p>

## 正文

接下来说说搭建这个博客的技术细节。  

正好之前就有关注过 [GitHub Pages](https://pages.github.com/) + [Jekyll](http://jekyllrb.com/) 快速 Building Blog 的技术方案，非常轻松时尚。

其优点非常明显：

* **Markdown** 带来的优雅写作体验
* 非常熟悉的 Git workflow ，**Git Commit 即 Blog Post**
* 利用 GitHub Pages 的域名和免费无限空间，不用自己折腾主机
* 如果需要自定义域名，也只需要简单改改 DNS 加个 CNAME 就好了
* Jekyll 的自定制非常容易，基本就是个模版引擎

---

配置的过程中也没遇到什么坑，基本就是 Git 的流程，相当顺手

大的 Jekyll 主题上直接 fork 了 Clean Blog（这个主题也相当有名，就不多赘述了。唯一的缺点大概就是没有标签支持，于是我给它补上了。）

本地调试环境需要 `gem install jekyll`，结果 rubygem 的源居然被墙了……后来手动改成了我大淘宝的镜像源才成功

第二天考虑中文字体的渲染，fork 了 [Type is Beautiful](http://www.typeisbeautiful.com/) 的 `font` CSS，调整了字号，适配了 Win 的渣渲染，中英文混排效果好多了。

## 后记

非常感谢Hux博客的分享，在此记录学习语音的点点滴滴，个人研究语言纯粹是出于个人兴趣，之前在CSDN 上也写过一些博客， 所以在这里记录有关语音学习的一些细节，部分源码也会进行讲解

—— ZhangNian 后记于 2015.10


