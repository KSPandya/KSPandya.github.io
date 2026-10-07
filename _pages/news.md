---
layout: page
title: news
permalink: /news/
nav: true
nav_order: 3
---

<div class="post">

{% if site.announcements.enabled %}
  {% include news.liquid %}
{% else %}
  <p>No news items found.</p>
{% endif %}

</div>
