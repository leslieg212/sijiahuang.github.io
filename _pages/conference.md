---
layout: archive
title: "Conference Presentations"
permalink: /conference/
author_profile: true
redirect_from:
  - /conference
---

{% include base_path %}
---

{% assign sorted_collection = site.portfolio | sort: 'weight' | reverse %}

{% for post in site.conference %}
  {% include archive-single.html %}
{% endfor %}

