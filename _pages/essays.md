---
title: Essays
layout: archive
permalink: /essays/
author_profile: true
---

I have subdivided my essay writings into these areas. Hope you enjoy!

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.cats | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
