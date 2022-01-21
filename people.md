---
layout: page
title: titles.people
permalink: /people/
---

## {% t headings.principal_investigator %}

{% assign pis = site.data.people | where: "title", "pi"  %}
{% include people.html people = pis %}

## {% t headings.postdocs %}

{% assign postdocs = site.data.people | where: "title", "postdoc"  %}
{% include people.html people = postdocs %}

## {% t headings.phd_students %}

{% assign phds = site.data.people | where: "title", "phd"  %}
{% include people.html people = phds %}

## {% t headings.masters_students %}

{% assign masters = site.data.people | where: "title", "master"  %}
{% include people.html people = masters %}

## {% t headings.interns_ras %}

{% assign interns = site.data.people | where: "title", "intern"  %}
{% include people.html people = interns %}

## {% t headings.alumni_and_their_next_step %}

### {% t headings.masters_students %}

{% assign alumni_masters = site.data.alumni | where: "title", "master" %}
{% include people_alumni.html people = alumni_masters %}

### {% t headings.interns_ras %}

{% assign alumni_interns = site.data.alumni | where: "title", "intern" %}
{% include people_alumni.html people = alumni_interns %}
