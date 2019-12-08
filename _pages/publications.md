---
layout: archive
title: "**Lab Works"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
 Action Control and Cognition Lab<u><a href="{{https://actioncontrolcognitionlaboratory.wordpress.com/}}"></a>.</u>
{% endif %}


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
