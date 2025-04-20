---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on [Google Scholar](https://scholar.google.com/citations?user=zQ5_q6IAAAAJ&hl=en).

## Pre-Prints and Working Papers

<ol reversed> {% for post in site.publications reversed %}
  {% if post.note == 'preprint' %}
    <li>{% include archive-single-publication.html %}</li>
  {% endif %}
{% endfor %}</ol>


## Peer-Reviewed Publications

{% include base_path %}

<ol reversed> {% for post in site.publications reversed %}
  {% if post.note != 'preprint' %}
    <li>{% include archive-single-publication.html %}</li>
  {% endif %}
{% endfor %}</ol>


## Software

1. Dorador, A. (2017). R package `analytics` (3.0), [*CRAN*](https://cran.r-project.org/web/packages/analytics/index.html) (formerly). >19K downloads (April 2025).
2. Dorador, A. and Thygesen, U.H. (2016). R package `complexplus` (2.1), [*CRAN*](https://cran.r-project.org/web/packages/complexplus/index.html). >45K downloads (April 2025).
3. Dorador, A. (2016). R package `powerplus` (3.1), [*CRAN*](https://cran.r-project.org/web/packages/powerplus/index.html) (formerly). >33K downloads (April 2025).
{: reversed="reversed"}
