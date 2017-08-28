---
layout: post
title: HELLO WORLD
category: START
---
<h4>Category</h4>
<ul>
    //这里使用了 Jekyll 语法，会被编译，所以加多个"\"
    {\% for category in site.categories %\}
    <li><a href="/categories/{\{ category | first }\}/" title="view all
posts">{\{ category | first }\} {\{ category | last | size }\}</a>
    </li>
    {\% endfor %\}
</ul>

Next you can update your site name, avatar and other options using the _config.yml file in the root of your repository (shown below).

![_config.yml]({{ site.baseurl }}/images/config.png)

The easiest way to make your first post is to edit this one. Go into /_posts/ and update the Hello World markdown file. For more instructions head over to the [Jekyll Now repository](https://github.com/barryclark/jekyll-now) on GitHub.
