---
layout: post
title: "Recovery all the stuffs in New year"
date: 2016-03-14 16:29:46 -0700
comments: true
categories: 
---

*2008-2012: 读大学，2012-2016: 工作。我好期待下一个四年会是怎样的风景*

{% img left /images/path.jpg 1024 768 'image' 'images' %}



###How to write Octopress Blog in two computors?

Damn it!  
两年前搞出个这么个东西，一直想向上post新东西。今天又探了许多坑。  
又对*Octopress*和*Github*加深了些理解。  

Please make sure **push source branch to github** whenever finishing your edit.  

```
$ rake generate
$ git add .
$ git commit -am "Some comment here." 
$ git push origin source  # update the remote source branch 
$ rake deploy             # update the remote master branch
```

And if you switch your machine, you need to pull changed before editing.

```
$ cd octopress
$ git pull origin source  # update the local source branch
$ cd ./_deploy
$ git pull origin master  # update the local master branch
```

Please see details: [Clone Your Octopress to Blog From Two Places](http://blog.zerosharp.com/clone-your-octopress-to-blog-from-two-places/)
`rake preview`后总是按`Ctrl+Z`结束，然后每次再preview时port都被占用。原来人家的命令是**`Ctrl+C`**  

`Git`总是用不熟练，不能每次换机器更新都删掉工程重来一遍哇！  


###这两年发生了什么？

发生了很多～  
最近最大的感悟：**知行合一**  

看了很多书和文章，想了很多道理，这些都是Input。把书中看到的知识用与实践，在结合自己的经历把自己的感悟表达出来，这些是Output。这两年Input很多，Output很少，还是很差劲。  

任何的Output都给了未来的我极大的信心。看过去留下来的东西也很感动。  

以后会经常更新这个博客，加入很多好东西来玩，顺便学点新东西，Html和Ruby。  

折腾这些东西并没有多大的意义，可我就是享受做成一件事的过程！

