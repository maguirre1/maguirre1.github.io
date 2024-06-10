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
* Ph.D in Biomedical Informatics, Stanford University, 2025 (planned).
* M.S. in Statistics, Stanford University, 2023.
* B.A. in Applied Mathematics, *cum laude*, Harvard University, 2017.

Work experience
======
* Fall 2019-Present: Ph.D student in Biomedical Informatics with [Jonathan Pritchard](https://web.stanford.edu/group/pritchardlab/home.html), at Stanford University 
  * Currently working on network-based models to assess the genetic architecture of complex traits.
  * Summer 2023: Bioinformatics Intern at [Guardant Health](https://guardanthealth.com). Performed application development for the [INFINITY](https://guardanthealth.com/guardantinfinity/) platform.

* Fall 2017-Summer 2019: Research data analyst with [Manuel Rivas](https://med.stanford.edu/rivaslab.html) and [James Priest](https://priestlab.stanford.edu/), at Stanford University 
  * Conducted large-scale studies in genetic epidemiology and contributed to the [Global Biobank Engine](https://biobankengine.stanford.edu/).

* Summer 2015-Spring 2017: Undergraduate researcher in the [MacArthur Lab](https://macarthurlab.org/) and [Data Science Platform](https://www.broadinstitute.org/data-sciences-platform), at the Broad Institute of Harvard and MIT 
  * Contributed to data quality control for the [gnomAD](https://gnomad.broadinstitute.org/) project
 
Awards
======
* Teaching Award, Stanford Department of Biomedical Data Science (2022)
* PhD Fellowship, Microsoft Research (2021)
* Reviewers' choice abstract, American Society of Human Genetics (ASHG) Annual Meeting (2020)

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
  
Service
======
* Student Representative, Stanford Department of Biomedical Data Science (2022-23)
* Peer Mentor, Stanford Biosciences (2020-2022)
* Research Mentor, Stanford Summer Research Program (SSRP, 2018)
