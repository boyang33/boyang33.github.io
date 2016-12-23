---
layout: post
title:  "Maven笔记"
date:   2016-12-23 15:14:47
categories: jekyll update
---
# Maven的配置文件pom.xml
简介：

什么是POM？

POM是项目对象模型(Project Object Model)的简称,它是Maven项目中的文件，使用XML表示，名称叫做pom.xml。在Maven中，当谈到Project的时候，不仅仅是一堆包含代码的文件。一个Project往往包含一个配置文件，包括了与开发者有关的，缺陷跟踪系统，组织与许可，项目的URL，项目依赖，以及其他。它包含了所有与这个项目相关的东西。事实上，在Maven世界中，project可以什么都没有，甚至没有代码，但是必须包含pom.xml文件。

概览

下面是一个POM项目中的pom.xml文件中包含的元素。注意，其中的modelVersion是4.0.0，这是当前仅有的可以被Maven2&3同时支持的POM版本，它是必须的。

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
