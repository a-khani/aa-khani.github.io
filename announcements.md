---
layout: page
title: Blog
nav_exclude: true
description: Ali's depository of updates.
---

# Blog

Blog posts are stored in the `_blog` directory and rendered according to the layout file, `_layouts/announcement.html`.

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}
