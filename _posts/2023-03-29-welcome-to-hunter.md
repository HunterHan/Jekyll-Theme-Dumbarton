---
layout: post
title:  "欢迎来到憨憨的博客！"
description: "一位技术“憨憨”的博客建站心路历程"
type: card-dated
date:   2023-3-29 22:01:21 +0800
categories: intro update
image: http://placehold.it/750X300?text=Header+Image # for local images, place in /assets/img/posts/
caption:
last-updated: 2023-3-29 22:01:21 +0800
categories: post
tag: 关于
author: 是憨憨啊
card: card-2
---
## 前言
你好，我是憨憨！欢迎来到我的博客。其实之前一直有过在Github上建立自己主页/博客的想法，但最终一直没有找到顺手的工具，再加上博客的需求不是那么迫切，而且不知道要些什么东西，博客建站计划就一次次搁浅了。这次恰好正在学习[*<u>王老师</u>*][will-ww]的[*<u>开源软件课程</u>*][oss101]，其中布置了一项关于博客建站的作业，算是推动了我的博客建站伟业吧hhh。

在本科阶段其实也因为课程的需要接触过前端一些内容，但是由于对后期职业规划的不确定、不知道自己将来是否从事相关的工作，便没有深入去学习，只是知道个大概，然后学学框架简单使用就上路了。之后开始跟讨论班一些学长学姐在做的一个小项目，便跟着开始看React、Ant Design等内容。一开始勉勉强强能玩得转吧，就从从UI网站拷贝拷贝组建然后调一调布局。但由于底盘不稳固、基础不牢，到了后期框架复杂度和代码量上来之后，开始有些吃力，最后我的前端之路几乎就止步于React的异步问题。

这次之所以能够完成博客搭建，非常重要的一点就是[*<u>Tie学长</u>*][tie-github]在布置这项作业时，写了非常详细的[*<u>文档和样例</u>*][doc-github]，并且提供的工具也是博客搭建的热门工具，对非开发的同学十分友好，也消除了我对前端的“恐惧”。

## 博客主题选取
我的对于博客建站思路是想形成一种类似学术简历的模板样式，能够规整地展示论文、项目等内容。因此，我在Jekyll的主题库中选择了这个主题。

## 博客页面布局及其设计思路
博客首页布局采用上下结构。除了顶层导航栏之外，采用头像+个人介绍/教育背景作为上片，将详细分类罗列展示作为下片。布局简约明了。

## 博客功能实现及其技术选择
博客主要的功能主要就是博客发布。
关于技术选取，我希望
Jekyll是一款主流静态网站/博客建站工具。其能够将平文本转化为静态网站与博客的，
Jekyll具备以下特点：
> 一、轻量简单
  Jekyll以Markdown格式进行页面和发布的配置编写，写作效率更高，可以免除写作者对前端样式的繁琐思考，让其专心内容本身。同时，其以yml格式配置数据内容，表达能力强、结构明晰、易于维护。

> 二、社区支持度较高
  Jekyll有完善的文档、丰富的资源以及高活跃度的论坛。完备的文档和Quick Start可以让你快速上手，丰富的论坛资源可以
  让你探索更多的设计主题、思路，而且有助于调试时快速定位问题并解决。

> 三、github支持度高
  Github自带jekyll引擎，无需部署静态页面，只需项目源码即可。即可以直接在GitHub上编写与修改，相较于传统方式相比更加便利。

Jekyll也存在一些挑战与缺点：
> 一、环境搭建
  Jekyll起环境是比较费事的。一个是它对Windows系统不友好，需要让Windows系统开启Linux功能才能勉强进行配置安装。另一个是即便在Linux环境下，Jekyll在安装时也是比较严谨的，通过rvm以外的方式安装比如apt-get，则容易失败。

> 二、编译速度慢
  Jekyll是由Ruby编写的，而ruby作为面向对象高级解释型语言，执行效率比编译型语言要低。而同样基于面向对象高级解释型语言，基于Nodejs的hexo在V8引擎的加持下速度相比Ruby有了显著提升。

## 博客样式设计及其美学参考

## 博客制作过程中的问题与解决方案
最主要的问题还是一开始环境的问题。关于gem和ruby的安装费了很多事，而且还没配好。最终解决方案的话，就把之前的全部清掉，用rvm的方式进行安装。而且rvm似乎对win不太友好，因此最后还是在另一台Ubuntu上搞定的。


最后，还是整个经典绝活以传统保留曲目来结束这第一篇博客：
```cpp
#include <iostream>
using namespace std;

int main(int argc, char** argv){

  cout << "Hello World!" << endl;

  return 0;
}
```
{% highlight cpp %}
#include <iostream>
using namespace std;

int main(int argc, char** argv){

  cout << "Hello World!" << endl;

  return 0;
}

{% endhighlight %}

## 参考
https://jekyllrb.com/

https://zhuanlan.zhihu.com/p/368407566


[will-ww]: https://github.com/will-ww
[oss101]: https://github.com/X-lab2017/oss101
[tie-github]: https://github.com/TieWay59
[doc-github]: https://github.com/X-lab2017/oss101/issues/33