---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% for paper in site.data.publications %}
  {% include paper-card.html paper=paper %}
{% endfor %}
