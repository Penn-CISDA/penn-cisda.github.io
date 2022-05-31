---
layout: page
title: People
---
<style type="text/css">
    .people { 
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        text-align: center;
    }
</style>

<h1>Current CISDA Members</h1>
<p>
  <div class="people">
    {% for person in site.data.people %}
      {% if person.status == "current" %}
        {% include person.html name=person.name img=person.img url=person.url %}
      {% endif %}
    {% endfor %}
  </div>
</p>

<h1>Former CISDA Members</h1>
<p>
  <div class="people">
    {% for person in site.data.people %}
      {% if person.status == "former" %}
        {% include person.html name=person.name img=person.img url=person.url %}
      {% endif %}
    {% endfor %}
  </div>
</p>