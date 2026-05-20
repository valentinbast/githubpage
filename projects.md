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



---
{% else %}
*No projects found in `_data/projects.yml`. Please ensure the file exists and is formatted correctly.*
{% endfor %}
