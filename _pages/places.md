---
layout: archive
title: places
permalink: /places/
date:
modified:
excerpt:
image:
  feature:
  teaser:
  thumb:
ads: false
comments:
breadcrumbs:
published: true
---

<div class="tiles">
{% for post in site.categories.places %}
  {% include post-grid.html %}
{% endfor %}
</div>
