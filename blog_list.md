---
layout: default
title: Blog List
---
# All my blogs12  

{% for post in site.posts %}
 - [{{ post.title }}]({{ post.url }})  
 time: {{ post.date }}  
 tag: {% for tag in post.tags %}{{ tag }} {% endfor %}
{% endfor %}
