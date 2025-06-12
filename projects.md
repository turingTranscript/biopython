---
layout: page
title: Projects
description: A feed containing all of the class projects.
---

# Projects

{% assign projects = site.projects | reverse %}
{% for project in projects %}
{{ project }}
{% endfor %}
