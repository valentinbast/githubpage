---
layout: page
title: Blog
permalink: /blog/
---

## Blog

Welcome to the blog. I write short posts about the projects I build, problems I solve, and what I learn along the way.

{% if site.posts.size > 0 %}
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }}) — {{ post.date | date: "%B %-d, %Y" }}
{% endfor %}
{% else %}
No posts yet. Create a new post in the `_posts/` folder to get started.
{% endif %}
