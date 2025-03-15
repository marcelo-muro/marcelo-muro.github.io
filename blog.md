---
layout: default
title: "Blog"
permalink: /blog/
---

## 📝 Blog Posts

Welcome to my blog! Here, I share insights on **modeling & simulation, Modelica, novel power plants and multi-energy systems**.  

## 📚 Recent Posts  

{% for post in site.posts %}
- 📅 **{{ post.date | date: "%B %d, %Y" }}** – [**{{ post.title }}**]({{ post.url }})
{% endfor %}

---