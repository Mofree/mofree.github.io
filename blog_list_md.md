---
layout: default
title: Blog List
---

# Latest Posts Test2

{% for post in site.posts %}
  [{{ post.title }}]({{ post.url }})  
  {{ post.excerpt }}  
{% endfor %}
