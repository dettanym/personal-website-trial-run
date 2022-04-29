---
title: Research
layout: collection
collection: publications
permalink: /publications/
entries_layout: grid
classes: wide
---

{% include base_path %}

{% for post in site.publications reversed %}
  {% include default.html %}
{% endfor %}
