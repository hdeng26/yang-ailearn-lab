---
title: "News"
layout: textlay
excerpt: "Yang's AiLearn Lab at Western University."
sitemap: false
permalink: /allnews.html
---

<div class="well">
<h4>News</h4>

{% for article in site.data.news limit:9 %}
<div class="news-entry">
  <div class="news-date">
    {{ article.date }}
  </div>
  <div class="news-headline">
    {{ article.headline }}
  </div>
</div>
{% endfor %}

<h4><a href="{{ site.url }}{{ site.baseurl }}/allnews.html">... see all News</a></h4>
</div>
