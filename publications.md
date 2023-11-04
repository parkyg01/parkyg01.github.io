---
layout: default
title: "Publications"
---

#### Peer-Reviewed Publications

{% for paper in site.data.publications %}
- **[{{paper.venue}} {{paper.year}}]** {{paper.title}}. <br>
{{paper.authors}}.<br>
*{{paper.book}}*, {%if paper.place %} {{paper.place}}, {% endif %}{{paper.month}} {{paper.year}}{% if paper.etc %} ({{paper.etc}}){% endif %}.
{% endfor %}
