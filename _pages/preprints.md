---
layout: archive
title: "Preprints"
permalink: /preprints/
author_profile: true
---

Here, you find a list of my current preprints:

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
