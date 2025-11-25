---
layout: default
title: Home
---

# 최근 포스트

{% for post in site.posts %}

  <article>
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p class="post-meta">{{ post.date | date: "%Y년 %m월 %d일" }}</p>
    <p>{{ post.excerpt }}</p>
  </article>
{% endfor %}
