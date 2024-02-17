---
title: "Videos"
layout: textlay
sitemap: false
permalink: /allnews.html
---

## Videos

<div class="jumbotron">
{% for article in site.data.news %}
<b>{{ article.date }}</b>

{{ article.headline }}
{% endfor %}
</div>
