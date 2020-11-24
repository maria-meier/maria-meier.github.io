---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

This site is currently under construction. In the meantime, you find a full list of my publications [here](/cv).

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<sup>*</sup> Equal authorship statement