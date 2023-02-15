---
layout: archive
title: "Publications"
permalink: /
author_profile: true
---

You can find my most recent articles on my [Google Scholar profile](https://scholar.google.com/citations?user=kqwH9FAAAAAJ&hl=en&authuser=2).

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
