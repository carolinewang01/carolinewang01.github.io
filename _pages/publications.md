---
layout: publications
title:
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  This page is may be out of date. You can find an up-to-date list of my articles on my <u><a href='{{site.author.googlescholar}}'> Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single-publication.html %}
{% endfor %}
