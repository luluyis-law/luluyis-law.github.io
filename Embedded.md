---
layout: page
title: Embedded
---

### 最新文章

{% for post in site.posts %}
  <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>
{% endfor %}
