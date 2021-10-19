---
layout: page
title: titles.theses
permalink: /theses/
---

<h1>Masters thesis</h1>
{% assign masters = site.data.theses | where: "degree", "master" | sort: 'date' | reverse %}

<ol reversed start="{{ masters.size }}">
{% for thesis in masters %}
<li>
{% include thesis.html
    title=thesis.title
    author=thesis.author
    supervisors=thesis.supervisors
    degree=thesis.degree
    university=thesis.university
    date=thesis.date
    links=thesis.links
%}
</li>
{% endfor %}
</ol>
