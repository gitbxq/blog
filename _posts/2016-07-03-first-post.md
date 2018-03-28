---
layout: default
title: 教你如何使用Jekyll
---
# 教你如何使用Jekyll

Zhang Zhensheng

## 1. 引言

![]({{ site.baseurl }}/img/1.png)

## 2. 参考资料

[Jekyll 中文文档](http://jekyll.bootcss.com/docs/home/)

[阮一峰老师的指导](http://www.ruanyifeng.com/blog/2012/08/blogging_with_jekyll.html)

## 3. 开始

* 系统环境是 Windows 10 x64

* 先安装[Ruby](http://www.ruby-lang.org/en/downloads/)

* 再安装[RubyGems](http://rubygems.org/pages/download)

* 借助RubyGems安装Jekyll

	`gem install jekyll`

* 安装完Jekyll，生成默认的目录结构

	`jekyll new myblog`

	然后进入myblog文件夹执行：

	`jekyll serve`

	然后用浏览器打开 http://localhost:4000/myblog/ 就可以看到博客啦（只是本地预览）！

* 将博客发布到线上

	首先安装Git，然后在myblog里开分支（gh-pages），写完博客后将分支推到远程，就可以通过指定url访问了，比如 [https://zhictory.github.io/jekyll/](https://zhictory.github.io/jekyll/)

## 4. 进阶

* 怎么用jekyll写博客？

## 5. 结语

这是我第一次建立博客，只见雏形，仍有很长的路要走。

感谢朋友[Charles Qiu](https://github.com/QMonkey)不吝赐教，给我指明一个建立博客的方向。

感谢朋友[zhzhzh122333](https://github.com/zhzhzh122333)和我的主管小林哥的鼓励和分享。

感谢[long-haul](https://github.com/brianmaierjr/long-haul)的作者[Brian Maier Jr.](https://github.com/brianmaierjr)的开源分享，本博客采用此主题作为主题。

感谢[Jekyll文档](http://jekyll.bootcss.com/)和所有参考资料的开发人员。
