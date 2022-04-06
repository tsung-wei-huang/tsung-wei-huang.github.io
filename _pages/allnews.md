---
title: "TW's Research Group - News"
layout: textlay
excerpt: "TW's Research Group - News"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}

<span class="badge-pill badge-info">{{ article.date }}</span>
<p><em>{{ article.headline }}</em></p>

{% if article.image %}
<center><div style="max-width: 300px;">
<img src="{{ article.image }}" style="width: 100%"/>
</div></center>
{% endif %}

{% endfor %}
