---
layout: archive
title: "Conference Presentations"
permalink: /conference/
author_profile: true
redirect_from:
  - /conference
---

{% include base_path %}
**Conference Presentations**<br />
---


{% assign sorted_portfolio = site.portfolio | sort: 'weight' %}
{% for post in sorted_portfolio %}
  {% include archive-single.html %}
{% endfor %}

