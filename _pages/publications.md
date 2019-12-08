---
layout: archive
title: "**Lab Works"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
 
Translation frequency constraints language non-selective
activation under working memory load and task-demands (ongoing), Action Control and Cognition Lab<u><a href="{{https://actioncontrolcognitionlaboratory.wordpress.com/}}"></a>.</u>
{% endif %}


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
