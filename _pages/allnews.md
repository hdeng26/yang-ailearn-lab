---
title: "News"
layout: textlay
excerpt: "Yang's AiLearn Lab at Western University."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<div class="news-item">
  <div class="news-date">{{ article.date }}</div>
  <div class="news-headline">{{ article.headline }}</div>
</div>
{% endfor %}
