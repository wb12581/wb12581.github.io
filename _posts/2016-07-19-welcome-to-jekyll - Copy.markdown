---
layout: post
title:  "这是我的第一篇博客"
date:   2018-01-11 16:50:45 +0200
categories: jekyll update
---
这是我的第一篇基于github构建的jekyll博客

下面分享我学习构建博客的教程链接:

[Mac下Jekyll安装][jekyll-install] 
[Mac下使用Jekyll和github搭建个人博客][jekyll-github]. 

以上两篇博客教程十分详细,希望大家可以在闲暇时间搭建属于自己的博客

下面是我搭建过程中用到的一些终端命令,希望可以帮到你哟~

{% highlight ruby %}
jekyll 运行调试 : 
1.cd 到 jekyll 项目所在目录下
2.jekyll build
3.jekyll server

提交全部变更到github :
1.git add -f *
(*表示所有,提交指定文件,则写 : 完整路径名/文件名.后缀名)
2.git commit -m “add test file”
3.git push origin master
{% endhighlight %}



[jekyll-install]:https://www.jianshu.com/p/07064eb79740
[jekyll-github]:http://blog.csdn.net/alex_my/article/details/56481922

