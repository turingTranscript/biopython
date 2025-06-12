---
layout: page
title: Announcements
description: A feed containing all of the class projects.
---

# Announcements

{% assign announcements = site.announcements | reverse %}
{% for annoucement in announcements %}
{{ annoucement }}
{% endfor %}
