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

{% if paginator.total_pages > 1 %}
<div class="pagination">
    {% if paginator.previous_page %}
    <a href="{{ paginator.previous_page_path }}">« Previous</a>
    {% endif %}
    {% if paginator.next_page %}
    <a href="{{ paginator.next_page_path }}">Next »</a>
    {% endif %}
</div>
{% endif %}

---