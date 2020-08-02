---
layout: default
title: Blog List
---
# All my blogs8  

{% for post in site.posts %}
 - [{{ post.title }}]({{ post.url }})  
{% endfor %}
