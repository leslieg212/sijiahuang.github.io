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

{% assign sorted_conference = site.conference | sort: 'weight' | reverse %}
{% for post in sorted_conference %}
  {% include archive-single.html %}
{% endfor %}
