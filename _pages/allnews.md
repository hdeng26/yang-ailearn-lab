---
title: "News"
layout: textlay
excerpt: "Yang's AiLearn Lab at Western University."
sitemap: false
permalink: /allnews.html
---

# News


{% for article in site.data.news %}
<div class="well">
  <b>{{ article.date }}</b>
  <p>{{ article.headline }}</p>
</div>
{% endfor %}