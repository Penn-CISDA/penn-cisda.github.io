---
layout: page
title: Guides
---
Check out our student-written guides to navigating a PhD in Penn CIS below. If 
you are interested in submitting your own guide, email us at 
[cisda-chairs@seas.upenn.edu](mailto:cisda-chairs@seas.upenn.ed).

<table>
    {% for guide in site.posts %}
        {% if guide.path contains 'guides' %}
            <tr>
                <td>{{ guide.date | date: "%b %-d, %Y" }}</td>
                <td><a href="{{ guide.url }}">{{ guide.title }}</a> <span style="color: grey"><i>{{ guide.submitted_by }}</i></span></td>
            </tr>
        {% endif %}
    {% endfor %}
</table>