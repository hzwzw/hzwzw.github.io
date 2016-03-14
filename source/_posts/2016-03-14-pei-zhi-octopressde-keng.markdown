---
layout: post
title: "配置octopress的坑"
date: 2014-06-22 16:16:14 -0700
comments: true
categories: 
---
##windows配置octopress的那些坑。

rake setup_github_pages有问题？  
rake deploy有问题？  
中文不能用？  

##rake setup_github_pages有问题？

郁闷指数：3星半  
最开始一直配置不成功，Bash和Cmd都不行，最后还是用Bash。（因为cmd里面不能用git命令，可能是环境变量的问题）  
要在rake安装的文件下操作，直到这个命令好使，提示能够输入repo URL了。OK，跳出这个坑，进入下一个坑。  

##rake deploy有问题？

郁闷指数： 4星  
怎么搞都不成功，一直提示git push被拒绝，但我一直可以pull下来，一直是最新代码啊。  
最后怎么解决的呢？  
删掉github里面的工程，重新搞了个最新的。（之前的工程里面有个index.html。可能是这个问题。）  

###中文不能用？

郁闷指数： 4星  
一直提示我utf-8有问题，可是我各种变量都设置好了呀！  
最后下了notepad++，设置编码格式为“UTF-8无BOM编码”，解决了。可能是Bash的问题，
之前一直是在Bash里面用vi写，最后用notepad++打开一看，乱七八糟的。


