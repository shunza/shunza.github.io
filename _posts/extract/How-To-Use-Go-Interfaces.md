---
layout: post
title: How To Use Go Interfaces
category: 摘录
keywords: 翻译,摘录,2018
---

## Don’t Do This

I occasionally give free Go consults and code review on top of my daily work. As such, I tend to read a lot of other peoples’ codes. And while this is really more of a feeling *, I’ve seen an increase in what I call “Java-style” interface usage.

This blog post is a Go specific recommendation from me, based on my experiences writing Go code, on how to use interfaces well.

For this blog post, the running example will span two packages: `animal` and `circus`. A lot of what I write about here is about code at the boundary of packages.