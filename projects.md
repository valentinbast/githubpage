---
layout: page
title: Projects
permalink: /projects/
---

## Projects

Below are a few of the projects I’m working on. Click through for details and source code.

{% for project in site.data.projects %}
### [{{ project.name }}]({{ project.url }})

{{ project.description }}

**Technologies:** 
{% for tag in project.tags %}
`{{ tag }}`{% unless forloop.last %}, {% endunless %}
{% endfor %}

---
{% endfor %}
