---
layout: page
cover-img: /assets/images/coriolis6.jpg
---

### Publications 
{% assign year = "3000" %}
{% assign ij = 0 %}{% assign ip = 0 %}{% assign it = 0 %}
{% for link in  site.data.publications %}
{% if link.date != year %}{% assign year = link.date %} <h2>{{ year }}</h2>{% endif %}
{% include publications.html %}

-------------------------
{% endfor %}


