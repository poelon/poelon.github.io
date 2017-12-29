---
layout: default
title:  "fichiers divers"
---

{% assign files = site.static_files %}
{% for file in files %}
{{ file.name }}
{% endfor %}
