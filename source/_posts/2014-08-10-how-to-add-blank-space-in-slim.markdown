---
layout: post
title: "如何在slim中添加空格"
date: 2014-08-10 16:56
comments: true
categories: ruby
tags: gem
---

在slim中如果想在两端代码中间添加一个空格，可以通过下面的方式

{% highlight slim %}
= link_to "btn1", "#", :class => "btn"
'
= link_to "btn2", "#", :class => "btn"
{% endhighlight %}

加一个`'`是不是很简单啊：）
