---
layout: archive
title: "Minimum viable products"
permalink: /mvps/
author_profile: true
---

{% if author.googlescholar %}
  %You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}
{% for post in site.mvps reversed %}
  {% include archive-single.html %}
{% endfor %}


* Developed screw classification web app for german based industry" 
  * Received azure credits of 10000USD.
