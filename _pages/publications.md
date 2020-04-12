---
layout: archive
title: "Publications"
author_profile: true
---

You can find it on [Google Scholar](https://scholar.google.com.pk/citations?user=_jXQiwMAAAAJ&hl=en) for now.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
