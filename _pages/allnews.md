---
title: "News"
layout: textlay
excerpt: "AML Lab."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<div class="row">
{{ article.date }}<br>{{ article.headline | markdownify}}
</div>
{% endfor %}
