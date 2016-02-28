---
layout: post
title: Jekyll博客小技能Tips
---

### 博客过程中，学到的一些小技能tips
{% highlight shell %}
// 从原来的hyde git上面clone下来
// 需要删除文件夹下的所有 .git 文件 
// 以便再把自己新建的git变成orgin
find . -name ".git" | xargs rm -Rf

// 和已经建好的github repository的git冲突，需要使用强制推送
git push -f

// 善用debugger和Liquid的site.posts字段，直接获取目前有哪些博文
c 'site.posts'
{% endhighlight %}