---
layout: splash
title: "Leviathianic"
---

{% for tag in site.tags %}
  <li>
    <a href="{{ site.baseurl }}/tags/{{ tag[0] }}/">{{ tag[0] }}</a> 
    ({{ tag[1].size }})
  </li>
{% endfor %}

<!--
this will display tag names and numbers

{% for tag in site.tags %}
    <li>{{ tag[0] }} ({{ tag[1].size }})</li>
{% endfor %}


-->
