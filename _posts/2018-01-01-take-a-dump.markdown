---
layout: post
title:  "Take a dump!"
date:   2018-01-05 12:55:14 -0600
categories: meta
---
Dumplings rock.

Here is a list of posts on this blog:
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

Do those links work?
