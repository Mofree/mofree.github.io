---
layout: default
title: Blog List
---
# All my blogs4  

{% for post in site.posts %}
 - [{{ post.title }}]({{ post.url }})  
Brief Content: {{ post.content }}  
{% endfor %}
