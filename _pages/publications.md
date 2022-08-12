---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find an up-to-date list of my publications in my [GoogleScholar](https://scholar.google.com/citations?user=s0fyR20AAAAJ&hl=en&oi=sra) profile.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
