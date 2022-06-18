---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Biomedical Informatics, Stanford University, 2024 (planned)
* B.A. in Applied Mathematics, *cum laude*, Harvard University, 2017

Work experience
======
* Fall 2019-Present: Ph.D student in Biomedical Informatics with [Jonathan Pritchard](https://web.stanford.edu/group/pritchardlab/home.html), at Stanford University 
  * Currently working on network-based models to assess the genetic architecture of complex traits.

* Fall 2017-Summer 2019: Research data analyst with [Manuel Rivas](https://med.stanford.edu/rivaslab.html) and [James Priest](https://priestlab.stanford.edu/), at Stanford University 
  * Conducted large-scale studies in genetic epidemiology and contributed to the [Global Biobank Engine](https://biobankengine.stanford.edu/).

* Summer 2015-Spring 2017: Undergraduate researcher in the [MacArthur Lab](https://macarthurlab.org/) and [Data Science Platform](https://www.broadinstitute.org/data-sciences-platform), at the Broad Institute of Harvard and MIT 
  * Contributed to data quality control for the [gnomAD](https://gnomad.broadinstitute.org/) project

<!-- 
Skills
======
* 
-->

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Presentations
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
<!--  
  
Service and leadership
======
* Currently signed in to 13 different slack teams -->
