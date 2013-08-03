---
layout: page
bio: This is a sample person's bio.
email: sample@person.com
github: sampleperson
image:
imageurl: /assets/img/Revhead.jpg
imagetitle: Sample Person
imagealt: Sample Person
imageattribution:
layout: profile
linkedin: sampleperson
name: Rev. Richard E. Baker
role: Founder & CEO
short: <a href="/team/sample-person">Sample Person</a> is the founder and CEO of the company.
twitter: sampleperson
type: employee
website: http://sampleperson.com/
---
{% include JB/setup %}

  <div class="span4">
    {% if page.imageurl %}
      <div>
        <img src="{{ page.imageurl }}" title="{{ page.imagetitle }}" alt="{{ page.imagealt }}" width="200" height="200" />
      </div>
    {% endif %}
	<ul>
      {% if page.linkedin %}
        <li><a href="http://www.linkedin.com/in/{{ page.linkedin }}">Connect on LinkedIn</a></li>
      {% endif %}

      {% if page.twitter %}
        <li><a href="http://twitter.com/{{ page.twitter }}">Follow on Twitter</a></li>
      {% endif %}
    </ul>
  </div>

  <div class="span8">
    <h1>
      {{ page.name }}
      <small>{{ page.role }}</small>
    </h1>

    {{ page.bio }}

    <ul>
      {% if page.github %}
        <li><a href="http://github.com/{{ page.github }}">Follow on GitHub</a></li>
      {% endif %}
    </ul>
  </div>
