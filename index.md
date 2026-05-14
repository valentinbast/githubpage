---
layout: home
title: Home
---

## Hello, Valentin

Welcome to my personal site. Here you’ll find my latest projects, experiments, and a blog about the topics that interest me. Mainly quantitative modelling of eco-societal interactions, Agent Based Models, green transition, methods so a wide array

### Explore

- [Projects](/projects/) — A showcase of apps, tools, and work I’m building.
- [Blog](/blog/) — Notes, tutorials, and stories from my learning journey.

### Featured

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%B %-d, %Y" }}
{% endfor %}


### About

I’m building software that solves problems and helps me learn fast. This page is a place to share what I’m working on and what I’m learning.
