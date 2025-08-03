---
layout: default
title: Publications
permalink: /publications/
---

# Publications

*indicating the corresponding author  
#indicating the co-first author

## Conference Papers

{% for paper in site.publications %}
- **{{ paper.title }}**{% if paper.corresponding %}<sup>*</sup>{% endif %}{% if paper.co_first %}<sup>#</sup>{% endif %}  
  Published in {{ paper.conference }}, {{ paper.year }}  
  [Download Paper]({{ paper.pdf_url }})
{% endfor %}
