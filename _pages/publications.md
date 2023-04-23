---
title: "Research and Publications"
header:
  overlay_image: header_dark.png
  overlay_filter: 0.6
excerpt: ">I was born not knowing and have had only a little time to change that here and there. <br/>
-- Richard Feynman, (Perfectly Reasonable Deviations from the Beaten Track, p. 396)"  
permalink: /publications/
author_profile: true
---
{% include base_path %}

### Research Interests

* Gravitational and Black Hole Physics
  * Black Hole Perturbation Theory
  * Quasinormal Modes of Black Holes
  * Internal Structure of Black Holes
  * Semi-classical Aspects of Gravity
  * Black Hole Shadows

---

### Published Papers
{% bibliography --file published %}

### Preprints
{% bibliography --file preprint %}

---

Please visit [my **INSPIRE-HEP** profile](https://inspirehep.net/literature?sort=mostrecent&size=25&page=1&q=exactauthor%3A%20S.Sarkar.12&ui-citation-summary=true&ui-exclude-self-citations=true) for bibliometrics and a possibly updated list of papers.

---

 {% include base_path %}

 {% for post in site.publications reversed %}
 {% include archive-single.html %}
 {% endfor %}
