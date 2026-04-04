---
layout: default
title: Blog
---

# My Blog 📝

Welcome to my blog where I share my university journey, fitness 
experiences and personal growth stories. I am a Computer Engineering 
student at UET Faisalabad, passionate about learning, building projects 
and living a healthy and active lifestyle.

---

## 🎓 University Posts

UET Faisalabad is one of the top engineering universities in Pakistan. 
I am studying Computer Engineering here and this section contains all 
my posts related to my academic journey, semester experiences, projects 
and university life.

![UET](https://images.unsplash.com/photo-1562774053-701939374585?w=800)

<ul>
{% for post in site.posts %}
  {% if post.categories contains 'University' %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%B %d, %Y" }}</li>
  {% endif %}
{% endfor %}
</ul>

---

## 🏃 Sports & Fitness Posts

Sports and fitness are an essential part of my daily life. I believe 
that a healthy body leads to a healthy mind and better academic 
performance. This section contains all my posts related to my fitness 
journey, workout routines, running, badminton and overall healthy 
lifestyle.

![Fitness](https://images.unsplash.com/photo-1526506118085-60ce8714f8c5?w=800)

![Running](https://images.unsplash.com/photo-1552674605-db6ffd4facb5?w=800)

![Badminton](https://images.unsplash.com/photo-1626224583764-f87db24ac4ea?w=800)

<ul>
{% for post in site.posts %}
  {% if post.categories contains 'Sports' %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%B %d, %Y" }}</li>
  {% endif %}
{% endfor %}
</ul>
