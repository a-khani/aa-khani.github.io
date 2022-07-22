---
layout: page
title: Bio
description: A little bit about me.
---

# Bio

{% assign people = site.staffers | where: 'role', 'Person' %}
{% assign num_people = people | size %}
{% if num_people != 0 %}

{% for person in people %}
{{ person }}
{% endfor %}
{% endif %}
