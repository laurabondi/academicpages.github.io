---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from: 
  - /research/
  - /research.html
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{[author.googlescholar](https://scholar.google.it/citations?view_op=list_works&hl=it&hl=it&user=wOecf5QAAAAJ)}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
