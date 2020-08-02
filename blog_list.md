---
layout: default
title: Blog List
---
# All my blogs7  

{% for post in site.posts %}
 - [{{ post.title }}]({{ post.url }})  
 date: {{ post.date }}  
 tags:
 {% for mytag in post.tags %}
  {{ mytag }}
 {% endfor %}  
{% endfor %}
