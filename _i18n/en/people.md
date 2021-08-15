
# Principal Investigator

<ul class="people">
{% assign pis = site.data.people | where: "title", "pi" %}
{% for person in pis %}
<li>
{% include person.html
    picture=person.picture
    name=person.name
    website=person.website
    cosupervisor=person.cosupervisor
    topics=person.topics
%}
</li>
{% endfor %}
</ul>

# Postdocs

<ul class="people">
{% assign postdocs = site.data.people | where: "title", "postdoc" %}
{% for person in postdocs %}
<li>
{% include person.html
    picture=person.picture
    name=person.name
    website=person.website
    cosupervisor=person.cosupervisor
    topics=person.topics
%}
</li>
{% endfor %}
</ul>

# PhD Students

<ul class="people">
{% assign phds = site.data.people | where: "title", "phd" %}
{% for person in phds %}
<li>
{% include person.html
    picture=person.picture
    name=person.name
    website=person.website
    cosupervisor=person.cosupervisor
    topics=person.topics
%}
</li>
{% endfor %}
</ul>

# Masters Students

<ul class="people">
{% assign masters = site.data.people | where: "title", "master" %}
{% for person in masters %}
<li>
{% include person.html
    picture=person.picture
    name=person.name
    website=person.website
    cosupervisor=person.cosupervisor
    topics=person.topics
%}
</li>
{% endfor %}
</ul>

# Interns/RAs

<ul class="people">
{% assign interns = site.data.people | where: "title", "intern" %}
{% for person in interns %}
<li>
{% include person.html
    picture=person.picture
    name=person.name
    website=person.website
    cosupervisor=person.cosupervisor
    topics=person.topics
%}
</li>
{% endfor %}
</ul>


# Alumni and their next step

#### Masters Students

<ul>
{% assign alumni_masters = site.data.alumni | where: "title", "master" | sort: "period.end"  | reverse %}
{% for person in alumni_masters %}
<li>
{% include person_alumni.html
    name=person.name
    website=person.website
    period=person.period
    next=person.next
%}
</li>
{% endfor %}
</ul>

#### Interns

<ul>
{% assign alumni_interns = site.data.alumni | where: "title", "intern" | sort: "period.end" | reverse %}
{% for person in alumni_interns %}
<li>
{% include person_alumni.html
    name=person.name
    website=person.website
    period=person.period
    next=person.next
%}
</li>
{% endfor %}
</ul>
