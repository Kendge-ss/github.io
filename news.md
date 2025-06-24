---
title: 最新ニュース
lang: ja
permalink: /news/
layout: default
---
# 最新ニュース

{% for n in site.data.news %}
- {{ n.date }} — [{{ n.title }}]({{ n.link }})
{% endfor %}
