---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles in [Google Scholar](https://scholar.google.com/citations?hl=en&user=-0znbV8AAAAJ&view_op=list_works&sortby=pubdate).

<sup>*</sup> denotes corresponding author.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
