# 我的数据库日记

## 20170612:+1:

1. 在虚拟机安装ubuntu
2. 熟悉一些常用命令如vim,rm,cd <文件夹名>等
3. vim的基本操作：
    * i：在当前字符的左边插入
    * I：在当前行首插入
    * a：在当前字符的右边插入
    * A：在当前行尾插入
    * o：在当前行下面插入一个新行
    * O：在当前行上面插入一个新
    * h: 向前移动一个字符
    * j: 向上移动一行
    * k: 向下移动一行
    * l: 向后移动一个字符
    * yy: 复制当前一行
    * dd:剪切当前一行
    * p: 粘贴内容到游标之后
    * P: 粘贴内容到游标之前
    * vim <文件名>: 有此文件打开此文件，没有创建并打开此文件
    * rm <文件名>：删除文件
4. 创建github用户，创建outlook邮箱
5. 基本文件夹操作：
* touch  file：创建文件
* mv file   file2：移动文件
* mv file  /home/linux/：移动文件
* ls -al：查看文件夹下文件  .
* cat  file：浏览文件

## 20170613:+1:

1. 简单介绍了linux历史
2. 人物介绍
3. 了解Linux的起源发展以及相关知识
4. git 基本命令操作
* 版本回退：git reset --hard commitID
* git log：查看已提交
* touch .gitignore：从仓库中忽略
* git format-patch -p1：生成patch
* git am patch-name: 打patch
5. 数据的删除与恢复,删除本地文件删除rm <文件名> 恢复 git checkout <文件名> ,仓库文件删除 git rm <文件名> 提交 git commit
6. 分支操作：
* git branch branch-name:创建新的分支
* git checkout -b branch-name：从任何的地方创建分支, 并切换到新创建的分支上.
* git branch -av：现实分支
* git checkout branch-name：分支切换
* git branch -D branch-name：删除分支

## 20170614:+1:

1. Linux 发行版介绍
2. Linux 操作系统组成
3. ubuntu 操作系统的安装
4. shell 解释器的介绍
5. 文本编辑器Vim的基本使用
6. git 远程仓库：
* git remote add origin url：添加远程仓库
* git fetch origin：将远程仓库信息同步到本地
* git push origin master：同步master分支
* git push -u origin :branch-name： 删除远程分支
## 20170615:+1:

1. 介绍了mysql的背景
2. 更新源
3. 安装mysql
4. Apache安装
5. workbench 安装
6. 了解MySQL 命令行操作
7. 建立三个数据库information,school,score
