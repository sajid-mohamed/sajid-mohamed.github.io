---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?user=z5ztMYAAAAAJ&hl=en).

{% bibliography --file publications %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
