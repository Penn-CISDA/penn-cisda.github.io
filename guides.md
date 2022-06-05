---
layout: page
title: Guides
---
Check out our student-written guides to navigating a PhD in Penn CIS below. If 
you are interested in submitting your own guide, email us at 
[cisda-chairs@seas.upenn.edu](mailto:cisda-chairs@seas.upenn.ed).

<div>
    {% for guide in site.posts %}
        {% if guide.path contains 'guides' %}
            <div style="display: flex; flex-direction: column; align-items: flex-start;">
            <a href="{{ guide.url }}">{{ guide.title }}</a>
        {% endif %}
    {% endfor %}
</div>