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

![UET Faisalabad Campus](https://uetfsd.edu.pk/wp-content/uploads/2021/09/DSC_0049-scaled.jpg)

<ul>
{% for post in site.posts %}
  {% if post.categories contains 'University' %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%B %d, %Y" }}</li>
  {% endif %}
{% endfor %}
</ul>

---

## 🏃 Sports Posts

In this section I share my fitness journey, workout routines, daily 
running experiences and my love for Badminton and Football.

<ul>
{% for post in site.posts %}
  {% if post.categories contains 'Sports' %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%B %d, %Y" }}</li>
  {% endif %}
{% endfor %}
</ul>
