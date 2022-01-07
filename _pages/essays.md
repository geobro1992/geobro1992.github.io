---
title: Essays
layout: archive
permalink: /essays/
author_profile: true
---

I have subdivided my essay writings into these areas. Hope you enjoy!



{% include base_path %}

{% assign ordered_pages = site.cats | sort:"order_number" %}

<div class="grid__wrapper">
{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div>


## Credits
- Some explanation text at the end of your document.