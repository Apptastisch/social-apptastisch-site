---
layout: default
title: Amazon Empfehlungen
---

# Amazon Empfehlungen

<ul class="affiliate-links">
{% for link in site.data.affiliate_links %}
  <li>
    <a href="{{ link.url }}" target="_blank" rel="noopener noreferrer nofollow">{{ link.title }}</a>
  </li>
{% endfor %}
</ul>
