---
title: Alumni
lang: en
permalink: /en/alumni/
layout: default
---
# Alumni

{% assign list = site.data.alumni | sort: "year" | reverse %}
{% for a in list %}
- **{{ a.name_en }}** ({{ a.year }}) — {{ a.position }}
{% endfor %}
