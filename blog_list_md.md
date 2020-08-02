---
layout: default
title: Blog List2
---

# Latest Posts Test2

{% for post in site.posts %}  
[{{ post.title }}]({{ post.url }})  
{{ post.excerpt }}  
{% endfor %}  
