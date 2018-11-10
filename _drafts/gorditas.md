---
layout: post
title:  "Gorditas — little fatties"
date:   2018-01-08 12:55:14 -0600
categories: been-there  future-noms
region:  [Central America, Mexico]
---

It's (often) not an insult at all to be labeled a little fatty!

Other Mexican dumplings:
<ul>
    {% for post in site.posts  %}
        {%  if post.region contains 'Mexico' and post.url <> page.url %} 
            <li>
                <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }} via the URL {{ post.url }}</a>
            </li>
        {%  endif %} 
    {% endfor %}
</ul>

Other Central American dumplings:  
<ul>
    {% for post in site.posts  %}
        {%  if post.region contains 'Central America' and post.url <> page.url  %} 
            <li>
                <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }} via the URL {{ post.url }}</a>
            </li>
        {%  endif %} 
    {% endfor %}
</ul>


    
This is {{ page.region | array_to_sentence_string }}.  Right?