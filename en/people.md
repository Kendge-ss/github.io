---
title: People
lang: en
permalink: /en/people/
layout: default
---
# Members

{% for p in site.data.people %}
- **{{ p.name_en }}** — {{ p.role }}
{% endfor %}
