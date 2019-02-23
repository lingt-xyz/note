---
layout: category
title:  Latex
---

{% for post in site.categories.latex %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ site.baseurl}}{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
