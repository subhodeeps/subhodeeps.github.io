---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

  You can also find my articles on <u><a href="{{https://inspirehep.net/literature?q=a%20S.Sarkar.12}}">my INSPIRE-HEP profile</a>.</u>

 {% include base_path %}

 {% for post in site.publications reversed %}
 {% include archive-single.html %}
 {% endfor %}
