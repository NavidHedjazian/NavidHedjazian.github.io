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

Hedjazian, N., & Kaminski, E. (2014), Defining a proxy for the interpretation of seismic anisotropy in non‐Newtonian mantle flows. <i>Geophys. Res. Lett., 41(20),</i> doi:10.1002/2014GL061372.
[PDF](https://agupubs.onlinelibrary.wiley.com/doi/pdf/10.1002/2014GL061372)
