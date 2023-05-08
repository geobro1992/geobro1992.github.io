---
title: "Research"
layout: archive
permalink: /research/
author_profile: true
---

Below are a selection of my main research topics to date.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

  <div class="grid__wrapper" style="width: 100%;">
{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div> 
