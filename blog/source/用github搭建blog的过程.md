title: "用github搭建blog的过程"
date: 2015-04-01 18:00:00 +0800
update: 2015-05-11 17:00:00 +0800
author: me
cover: ""
tags:
    - git
preview: 

---

### 开始上手

- 用Ink,生成静态的html.
- 申请github的帐号
- 在github上，申请博客的帐号。这个可以百度地到。

### 下面是比较重要的部分，网上没有讲到的。

- git branch gh-pages 新建gh-pages分支
- git checkout gh-pages 切换到 gh-pages分支
- git rm -rf . 清空gh-pages内的内容
- git add . 跟踪自己定义的文件
- git commit -m "..." 提交本次的修改
- git checkout -b gh-pages origin/gh-pages 切换分支（可以不做）
- git push origin gh-pages 远程更新


