---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Here is a list of my published and preprinted works. For a more reliably updated source, please refer to my <u><a href="https://scholar.google.com/citations?user=5IpsvZsAAAAJ&hl=en">Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
