---
layout: single
permalink: /essays/
collection: cats
entries_layout: grid
author_profile: true
---

{% include base_path %}

{% assign ordered_pages = site.cats | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
