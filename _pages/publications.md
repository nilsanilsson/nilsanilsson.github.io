---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.inspire %}
  You can also find my articles on <u><a href="{{author.inspire}}">my InspireHEP profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
