---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a current PhD student in computer science at the University of Colorado, Boulder. I am a member of the [CUPLV](https://plv.colorado.edu/) research group under the advisement of [Ashutosh Trivedi](https://ashut.bitbucket.io/).

My research interests are broadly centered around theoretical computer science, especially automata theory, logic, and computational complexity.

---

Publications
======

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

---

Teaching
=====

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
