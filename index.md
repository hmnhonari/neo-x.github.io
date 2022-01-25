---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
permalink: /
title: pages.home
---
{% include collage.html %}

## {% t headings.about_the_lab %}

{% tf about.md %}

## {% t headings.news %}

{% assign news = site.data.news | where: "hidden", nil | sort: 'date' | reverse %}
{% for note in news %}
* ({{ note.date | localize: "%B %Y" }}) {{ note[site.lang] }}
{% endfor %}
