---
title: 卒業生・修了生
lang: ja
permalink: /alumni/
layout: default
---
# 卒業生・修了生

{% assign list = site.data.alumni | sort: "year" | reverse %}
{% for a in list %}
- **{{ a.name }}** ({{ a.year }}) — {{ a.position }}
{% endfor %}
