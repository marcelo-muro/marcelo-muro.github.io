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

{% if site.total_pages > 1 %}
<div class="pagination">
    {% if site.previous_page %}
    <a href="{{ site.previous_page_path }}">« Previous</a>
    {% endif %}
    {% if site.next_page %}
    <a href="{{ site.next_page_path }}">Next »</a>
    {% endif %}
</div>
{% endif %}

---