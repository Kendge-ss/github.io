---
title: メンバー
lang: ja
permalink: /people/
layout: default
---
# メンバー一覧

{% for p in site.data.people %}
- **{{ p.name }}** — {{ p.role }}
{% endfor %}
