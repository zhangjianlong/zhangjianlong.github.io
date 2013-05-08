---
layout: post
title: "如何在本地部署jekyll并正确运行"
description: "如何在本地部署jekyll并正确运行"
category: 
tags: [jekyll]
---
{% include JB/setup %}


如何在本地部署jekyll，并正确运行<br>
1：ekyll使用Ruby编写的，所以要先配置Ruby环境,下载railsinstaller并安装，ruby和devkit也会被安装完成。<br>
2：输入gem install jekyll安装jekyll<br>
3：输入jekyll -version检查jikeyll版本信息<br>
4：输入git clone url  将远程库克隆到本地<br>
5：cd 到本库库目录下,输入jekyll -- server，在本地启动server<br>
6：在浏览器中输入localhost：4000，在本地运行<br>