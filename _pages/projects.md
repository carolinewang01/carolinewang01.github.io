---
layout: archive
title: Projects
permalink: /projects/
author_profile: true
redirect_from:
  - /portfolio
---

{% include base_path %}


{% for post in site.projects %}
  {% include archive-single.html %}
{% endfor %}

