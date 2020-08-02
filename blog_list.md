---
layout: default
title: Blog List
---
# All my blogs2  

{% for post in site.posts %}
 - [{{post.title}}]({{post.url}})  
Brief Content: {{post.excerpt}}  
{% endfor %}
