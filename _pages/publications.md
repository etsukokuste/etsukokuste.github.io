---
layout: publication
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my full publication list [here](https://scholar.google.com/citations?user=eY9gm7QAAAAJ&hl=ja&oi=ao).


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single-publications.html %}
{% endfor %}
