---
layout: default
title: Blog List3
---

# Latest Posts Test3

{% for post in site.posts %}  
[{{ post.title }}]({{ post.url }})  
{{ post.excerpt }}  
{% endfor %}  
