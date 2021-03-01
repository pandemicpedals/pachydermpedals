---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: Pandemic Pedals Collection
layout: collection
entries_layout: grid
output: true
classes: wide
author_profile: true
permalink: /pedals/
collection: pedals
sort_by: title
sort_order: reverse

header:
  teaser: /assets/images/header.jpg
  overlay_image: /assets/images/header.jpg
  overlay_filter: 0.8

pagination:
    enabled: true
    collection: pedals
    entries_layout: grid
---

{% for post in paginator.collection %}
  <h1>{{ post.title }}</h1>
{% endfor %}

{% if paginator.total_pages > 1 %}
<ul>
  {% if paginator.previous_page %}
  <li>
    <a href="{{ paginator.previous_page_path | prepend: site.baseurl }}">Newer</a>
  </li>
  {% endif %}
  {% if paginator.next_page %}
  <li>
    <a href="{{ paginator.next_page_path | prepend: site.baseurl }}">Older</a>
  </li>
  {% endif %}
</ul>
{% endif %}