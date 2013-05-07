---
layout: post
title: "git的常用命令"
description: "git的常用命令"
category: 
tags: [git]
---
{% include JB/setup %}

git --version                                   获取git的版本<br>
git config --global user.name"username"         配置用户名  <br>
git config --global user.email"useremail"       配置用户邮箱<br>
git config --global user.name                   查看用户名<br>
git config --global user.email                  查看用户邮箱<br>
git add .                                       添加新文件到版本库（所有文件，包括子目录，但不包括空目录）<br>
git commit -m “comment”                         提交并加双引号内的内容为注释<br>
git push -u origin master                       推入远程库<br>
git init                                        初始化新版本库<br>
git remote add origin 远程库版本的url           添加远程库版本的别名<br>
git remote                                      查看当前远程库<br>
git remote rm origin                            删除当前的远程库<br>
git clone <url>                                 克隆版本库<br>
