---
title: "News"
layout: textlay
excerpt: "Yang's AiLearn Lab at Western University."
sitemap: false
permalink: /allnews.html
---

<div class="well">
<h4>News</h4>

<p>{{ article.date }}<br>{{ article.headline | markdownify}}</p>
{% endfor %}

<h4><a href="{{ site.url }}{{ site.baseurl }}/allnews.html"></a></h4>

</div>
