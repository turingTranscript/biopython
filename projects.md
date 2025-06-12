---
layout: page
title: Projects
description: A feed containing all of the class announcements.
---

# Projects

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}
