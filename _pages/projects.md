---
layout: archive
title: projects
permalink: /projects/
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
{% for post in site.categories.projects %}
  {% include post-grid.html %}
{% endfor %}
</div>
