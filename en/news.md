---
title: News
lang: en
permalink: /en/news/
layout: default
---
# News

{% for n in site.data.news %}
- {{ n.date }} — [{{ n.title }}]({{ n.link }})
{% endfor %}
