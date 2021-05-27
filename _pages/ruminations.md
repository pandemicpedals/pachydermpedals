---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: Manic Ruminations
tagline: A place where I try to make sense of the turmoil in my head.

layout: collection
permalink: /ruminations/
collection: ruminations
entries_layout: list
output: true

classes: wide
author_profile: false
sort_by: date
sort_order: reverse

header:
  teaser: /assets/images/header_ruminations.jpg
  overlay_image: /assets/images/header_ruminations.jpg
  overlay_filter: 0.7

pagination:
    enabled: true
    collection: ruminations
    entries_layout: list
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