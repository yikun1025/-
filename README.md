
## 目录

- [介绍](#介绍)
- [目前需求](#目前需求)
- [个人博客功能](##个人博客所承担的功能)
- [Bugs and feature requests](#bugs-and-feature-requests)
- [Contributing](#contributing)


### 介绍

帮助设计师更方便快捷的建站，瓦解大平台

- 设计师需要更具**个性化**的个人展示作品集
- 网站的模板虽然多却不够**定制化**
- 部署+维护+设计**一体化平台**

```ad-quote
title: 关于博客
比如你想寻找一块「互联网自留地」，或是想要进行一些完整的而非碎片化的记录，或者想要避免无穷无尽的内容审查，又或者你只是不喜欢社交平台那杂乱的界面和不必要的互动，个人网站或博客总是一个更好的选择。
```

### 目前需求

<p style="text-indent:2em">1. 对个人网站域名的技术调研,重点在域名以及图床，服务器的技术方案寻求解决方案</p>
<p style="text-indent:2em">2. 目前已经拥有成熟的静态部署网站方案，可以在此基础上增加插件功能？修改特定模板，减少工作量。减少轮子</p>
```ad-note
title: 静态部署网站
技术上来讲，静态网站是指网页不是由服务器动态生成的。HTML、CSS 和 JavaScript 文件就静静地躺在服务器的某个路径下，它们的内容与终端用户接收到的版本是一样的。原始的源码文件已经提前编译好了，源码在每次请求后都不会变化。
```

#### 静态网站的好处:
- 加载时间更短，请求的服务器资源更少、更安全（值得商榷）。
- 传统上，静态网站更适合于创建只有少量网页、内容变化不频繁的小网站。
==可见，静态网站更加契合我们个人博客的需求==

这篇文章[10 大静态网站生成工具](https://zhuanlan.zhihu.com/p/260957368)
目前著名的静态网站有:
- [**Jekyll**](https://jekyllrb.com/)
- [**Hugo**](https://gohugo.io/)
- [**Hexo**](https://hexo.io/)
- ....


## 个人博客所承担的功能

个人博客所承担的首要功能是**学习过程的记录** 。我们都知道，输出和输入之间是有一个中间过程的，那就是学习笔记。注意，这里学习笔记的含义是广泛的，书籍的摘录、论文的翻译、实验的过程记录等，都可以算作学习笔记。这些内容的共同点是，它们更多的是原始材料的总结归纳，自己的想法比较少，即使有，也是零散不成体系的。因此，学习笔记很难作为纯粹的输出去发表，但是作为博客却没有任何问题，博客的最大优点就在于它的包容性。



### 调研文章

- [2020 年，如何才能拥有一个个人网站](https://sspai.com/post/59504)
- Hugo + GitHub Pages + Cusdis[免费的个人博客系统搭建及部署解决方案](https://www.pseudoyu.com/zh/2022/03/24/free_blog_deploy_using_hugo_and_cusdis/)

### 博客技术栈
-   [Hugo](https://gohugo.io/)：基础博客框架
-   [Love](https://github.com/dillonzq/LoveIt)[It](https://github.com/theme-next/hexo-theme-next)：Hugo 社区的一款博客主题
-   [Valine](https://valine.js.org/)：文章评论组件
-   [LeanCloud](https://leancloud.cn/)：评论数据云存储
-   Github：博客文件存储，Github Pages 和 Github Action 是两个使用的重要功能
-   Git：这里用作博客文件管理
-   Markdown：一种方便的写作语言
-   TOML：一种配置文件格式，用于文章开头的元数据定义
-   [Tencent Cloud](https://cloud.tencent.com/): 利用对象存储提供图床服务

