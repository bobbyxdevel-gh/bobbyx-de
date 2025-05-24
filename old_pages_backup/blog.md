---
layout: default
title: Blog
---

## Blog

Welcome to my blog! Posts coming soon.

If you are looking for posts, check the [blog index]({{ '/blog/' | relative_url }}) or see the latest below.

<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> <small>{{ post.date | date: "%b %d, %Y" }}</small></li>
  {% endfor %}
</ul>
