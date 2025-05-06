---
title: "News"
layout: textlay
excerpt: "Yang's AiLearn Lab at Western University."
sitemap: false
permalink: /allnews.html
---

# News

<div class="news-list">
{% for article in site.data.news %}
  <div class="news-item">
    <p class="news-date">{{ article.date }}</p>
    <p class="news-headline">{{ article.headline }}</p>
  </div>
{% endfor %}
</div>
