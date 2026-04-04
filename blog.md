---
layout: default
title: Blog
---

# My Blog 📝

Welcome to my blog where I share my university journey, fitness 
experiences and personal growth stories.

---

## 🎓 University Posts

<ul>
{% for post in site.posts %}
  {% if post.categories contains 'University' %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%B %d, %Y" }}</li>
  {% endif %}
{% endfor %}
</ul>

---

## 🏃 Sports Posts

<ul>
{% for post in site.posts %}
  {% if post.categories contains 'Sports' %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%B %d, %Y" }}</li>
  {% endif %}
{% endfor %}
</ul>
