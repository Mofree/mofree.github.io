---
layout: default
title: Blog List
---
**All my blogs**  

{% for post in site.posts %}
 - [{{ post.title }}]({{ post.url }})  
 date: {{ post.my_date }}  
 tag: {% for tag in post.tags %}{{ tag }} {% endfor %}
{% endfor %}
