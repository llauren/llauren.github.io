---
layout: page
title: the llaurén conspiracy
tagline: yes, i am really everyhere
---
{% include JB/setup %}

So here i am once more. Now this time i'm testing out what the Jekyll Bootsrap thingamajig
will do on Github pages. Originally i wanted to know if it's feasible to have a blog hosted
on Github pages but then i got lost somehow.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

Everything is unfinished.
Beware of falling letters.


