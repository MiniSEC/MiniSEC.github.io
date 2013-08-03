---
layout: page
active: true
bio:
  This is a sample person's bio.
email: sample@person.com
github: sampleperson
image:
  url: /images/sample-person.jpg
  title: Sample Person
  alt: Sample Person
  attribution:
layout: profile
linkedin: sampleperson
name: Rev. Richard E. Baker
role: Founder & CEO
short:
  <a href="/team/sample-person">Sample Person</a> is the founder and CEO of the company.
twitter: sampleperson
type: employee
website: http://sampleperson.com/
---
<div class="row">
  <div class="span4">
    {% if page.image %}
      <div id="profile-photo">
        <img src="{{ page.image.url }}" title="{{ page.image.title }}" alt="{{ page.image.alt }}" width="200" height="200" />
      </div>
    {% endif %}
  </div>

  <div class="span8">
    <h1>
      {{ page.name }}
      <small>{{ page.role }}</small>
    </h1>

    {{ page.bio }}

    <ul>
      {% if page.linkedin %}
        <li><a href="http://www.linkedin.com/in/{{ page.linkedin }}">Connect on LinkedIn</a></li>
      {% endif %}

      {% if page.twitter %}
        <li><a href="http://twitter.com/{{ page.twitter }}">Follow on Twitter</a></li>
      {% endif %}

      {% if page.github %}
        <li><a href="http://github.com/{{ page.github }}">Follow on GitHub</a></li>
      {% endif %}
    </ul>
  </div>
</div>
