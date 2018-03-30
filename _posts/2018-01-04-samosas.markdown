---
layout: post
title:  "Samosas"
date:   2018-01-08 12:55:14 -0600
categories: recipe
region:  [Asia, India]
---

<span style="border-bottom: 1px solid black;">*Essay question:*</span><br/>
Do Samosas really count as dumpings?  Why or why not?  Who gets to make that call?

<!--
Other Indian dumplings:
<ul>
    {% for post in site.posts  %}
        {%  if post.region contains 'India' and post.url <> page.url %} 
            <li>
                <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
            </li>
        {%  endif %} 
    {% endfor %}
</ul>

-->

Other Asian dumplings:  
<ul>
    {% for post in site.posts  %}
        {%  if post.region contains 'Asia' and post.url <> page.url %} 
            <li>
                <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
            </li>
        {%  endif %} 
    {% endfor %}
</ul>


    
<!-- 
    This is {{ page.region | array_to_sentence_string }}.  Right?
-->