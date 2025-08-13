---
title: Posts
layout: page
---


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>— {{ post.date | date: "%B %d, %Y" }}</small>
      {% if post.categories %}
        <span> | Categories: 
          {% for cat in post.categories %}
            {{ cat }}{% if forloop.last == false %}, {% endif %}
          {% endfor %}
        </span>
      {% endif %}
    </li>
  {% endfor %}
</ul>
