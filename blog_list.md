---
layout: default
title: Blog List
---
**All my blogs15**  

{% for post in site.posts %}
 - [{{ post.title }}]({{ post.url }})  
 date: {{ post.my_date }}  
 tag: {% for tag in post.tags %}{{ tag }} {% endfor %}
{% endfor %}

{% for tag in site.tags %}
{{ tag[0] }}  
{% for post in tag[1] %}[{{ post.title }}]({{ post.url }})  {% endfor %}
{% endfor %}
