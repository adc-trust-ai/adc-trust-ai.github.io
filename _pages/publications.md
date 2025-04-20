---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on [Google Scholar](https://scholar.google.com/citations?user=zQ5_q6IAAAAJ&hl=en).

Pre-Prints and Working Papers
======
<ol>{% for post in site.publications reversed %}
  {% if post.note == 'preprint' %}
    <li>{% include archive-single-publication.html %}</li>
  {% endif %}
{% endfor %}</ol>

Peer-Reviewed Publications
======
{% include base_path %}

<ol reversed> {% for post in site.publications reversed %}
  {% if post.note != 'preprint' %}
    <li>{% include archive-single-publication.html %}</li>
  {% endif %}
{% endfor %}</ol>

Software
======
My R packages
