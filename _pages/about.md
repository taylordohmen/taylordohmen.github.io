---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I recently graduated with a PhD in computer science from the University of Colorado Boulder, where I studied under the advisement of Professor [Ashutosh Trivedi](https://ashut.bitbucket.io/).

My research interests are broadly centered around theoretical computer science, including topics related to automata theory, optimization & leraning, formal logic, and computational complexity.

---

Publications
======

<script src="https://bibbase.org/show?bib=https://dblp.org/pid/251/3272.bib?param=1&jsonp=1&commas=true"></script>

<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->
  
---

Teaching
=====

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
