---
layout: archive
title: "Research and Publications"
permalink: /publications/
author_profile: true
---

  You can also find my articles on <a href="{{https://inspirehep.net/literature?q=a%20S.Sarkar.12}}">my INSPIRE-HEP profile</a>.

 {% include base_path %}

 {% for post in site.publications reversed %}
 {% include archive-single.html %}
 {% endfor %}
