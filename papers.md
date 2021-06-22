---
layout: default
title: Papers PAge
exclude: true
---
       
        {% for paper in site.data.papers %}
        {{ paper.authors }}
        "{{ paper.title }}",
        <em>{{ paper.journal }}</em>,
        {{ paper.year }},
        {% if paper.volume %} <strong>{{ paper.volume }}</strong>,{% endif %}
        {{ paper.pages }}.
        <a href="http://dx.doi.org/{{ paper.doi }}">[DOI]</a>
        {% endfor %}