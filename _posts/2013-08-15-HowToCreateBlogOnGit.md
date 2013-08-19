---
layout: default
title: How to create a blog on Github
---

{{ page.title }}
=========================

<p>{{ page.date|date_to_string}}</p>

Finally I create this blog successly. Now I plan to record the steps. 
###1. create git pages 
The main refer is [GitHubHelp](https://help.github.com/categories/20/articles).
I created pages with automatic generator as follows [see](https://help.github.com/articles/creating-pages-with-the-automatic-generator)

###2. create blog with jekyll
Install jekyll using the commond line: gem install jekyll
Create a parallel folder. It can be visited [here](http://ustc0324.github.io/jekyll_demo/)
see [blogging_with_jekyll](http://www.ruanyifeng.com/blog/2012/08/blogging_with_jekyll.html)
So we can create our blogs in a parallel folder. Just remember two things.
* _config.yml: baseurl: /jekyll_demo
* index.html: {{ site.baseurl }}{{ post.url }}

###3. understand how it works
see [build-static-sites-with-jekyll](http://yanping.me/cn/blog/2011/12/15/building-static-sites-with-jekyll/)
