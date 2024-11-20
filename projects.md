---
layout: page
title: Projects
permalink: /projects/
---

Here is the list of projects I've logged development for.

{% for project in site.projects %}
- #### [{{ project.name }}]({{ site.baseurl | append: project.url }})
  {{ project.excerpt }}
{% endfor %}
