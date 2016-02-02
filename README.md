# 修改记录

2016.02.02

1. 把评论系统改为符合国情的友言。
2. 添加博客作者和图片的侧边栏。
3. 把Logo和作者照片修改为可配置。

修改与增加的配置选项：

	[params]
	  Author = "博主姓名"
	  AuthorDes = "博主介绍"
	  Profile = "images/profile.jpg" # 博主头像
	  Logo = "images/logo.jpg" # 头部图片
	  UyanId = "1655689" # 友言id
	  comment = true # 开启评论
	  
2016.02.02

1. 把界面修改为中文
2. 添加Logo背景，在static/images/cover.jpg指定背景Logo。
3. 效果预览：[http://www.aicookie.com](http://www.aicookie.com)

---
![screenshot](https://raw.githubusercontent.com/dim0627/hugo_theme_aglaus/master/images/screenshot.png)

# Features

* Google Analytics
* Disqus
* Share Buttons(fb, twitter, google+, pocket)
* Eye-catching Image
* MicroData
* Readable text(Customized Vertical Rhythm).

# Installation

[hugoThemes#Installing Themes](https://github.com/spf13/hugoThemes#installing-themes).

# Configuration

**config.yaml**

``` toml
baseurl = "http://hugo.spf13.com/"
title = "Hugo Themes"
author = "Steve Francia"
copyright = "Copyright (c) 2008 - 2014, Steve Francia; all rights reserved."
canonifyurls = true
paginate = 3

[params]
  disqusShortname = "your disqus id." # optional
```

**example post**

``` toml
+++
title = "Getting Started with Hugo"
description = ""
tags = [
    "go",
    "golang",
    "hugo",
    "development",
]
date = "2014-04-02"
categories = [
    "Development",
    "golang",
]

image = "image.jpg" # optional
toc = false # optional, When set to FALSE this parameter, table of contents not appears in only this article.
+++

Contents here
```

# Contact us

Please mail to `dim0627@gmail.com` or SNS.

[https://www.facebook.com/daisuke.tsuji.735](https://www.facebook.com/daisuke.tsuji.735)

