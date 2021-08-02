---
layout: page
title: titles.publications
permalink: /publications/
---

## Preprints

<ul>
{% assign preprints = site.data.publications | where: "preprint", true | sort: 'date' | reverse %}
{% for paper in preprints %}
<li>
{% include paper.html
    title=paper.title
    authors=paper.authors
    venue=paper.venue
    date=paper.date
    links=paper.links
%}
</li>
{% endfor %}
</ul>

## Conference and Journal Papers

{% assign publications = site.data.publications | where: "preprint", nil | sort: 'date' | reverse %}
{% assign year_lastpaper = nil %}
{% for paper in publications %}
{% assign year_thispaper = paper.date | date: '%Y' %}

{% if year_lastpaper != year_thispaper %}
{% unless forloop.first %}
</ol>
{% endunless %}
<h1>{{ year_thispaper }}</h1>
<ol reversed start="{{ forloop.rindex }}">
{% endif %}

<li>
{% include paper.html
    title=paper.title
    authors=paper.authors
    venue=paper.venue
    date=paper.date
    links=paper.links
%}
</li>

{% assign year_lastpaper = year_thispaper %}
{% endfor %}
</ol>
