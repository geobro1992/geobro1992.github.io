---
title: Essays
layout: archive
permalink: /essays/
author_profile: true
---

Sample document listing for the collection `_cats`.

{% include base_path %}

{% assign ordered_pages = site.cats | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
