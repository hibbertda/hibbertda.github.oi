---
layout: page
permalink: /homeautomation/
title: Home Automation
---


{% for post in site.categories.HASS %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}