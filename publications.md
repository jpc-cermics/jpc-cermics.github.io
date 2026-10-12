---
layout: page
cover-img: /assets/images/coriolis6.jpg
---

### Publications 
{% assign year = "3000" %}
{%- comment -%} Category totals, counted DOWN in the loop below so that a number
stays attached to a given entry when new ones are added on top. The if/elsif/else
precedence must stay in sync with _includes/publications.html. {%- endcomment -%}
{%- assign ij = 0 -%}{%- assign iw = 0 -%}{%- assign ip = 0 -%}
{%- for link in site.data.publications -%}
{%- if link.AC -%}{%- assign ij = ij | plus:1 -%}{%- elsif link.PROC -%}{%- assign iw = iw | plus:1 -%}{%- else -%}{%- assign ip = ip | plus:1 -%}{%- endif -%}
{%- endfor -%}
{% for link in  site.data.publications %}
{% if link.date != year %}{% assign year = link.date %} <h2>{{ year }}</h2>{% endif %}
{% include publications.html %}

-------------------------
{% endfor %}


