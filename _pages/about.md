---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true 
redirect_from: 
  - /about/
  - /about.html
---

Co-founder of Olektr.ai, Aiming to develop products and research in the field
of computer vision, Deep Learning and Machine Learning.





---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
