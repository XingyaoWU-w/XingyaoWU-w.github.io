---
layout: archive
title: "Working Papers"
permalink: /works/
author_profile: true
---

{% include base_path %}

{% for post in site.works reversed %}
  {% include archive-single.html %}
{% endfor %}
