---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my papers on my <a href="https://scholar.google.com/citations?hl=en&user=uc8fGkMAAAAJ&view_op=list_works&sortby=pubdate">Google Scholar</a> profile.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
