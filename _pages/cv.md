---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
<hr style="text-align:left;margin-left:0;border-top:2px solid #6b7278"> 

## Education
-----
* **Indian Institute of Science Education and Research, Mohali** <br> BS-MS Dual Degree, Physics Major (2018 - 2023)
  * Cumulative GPA: 9.52/10 (till Semester 8)  
* **Apeejay School, Sheikh Sarai, New Delhi** <br> CBSE Board, Secondary and Senior Secondary School (2015 - 2018)
  * AISSCE, Class 12: 95.4% score
  * AISCE,  Class 10: 10.0/10 CGPA

## Research Experience
-----
* **Masters thesis project with [Prof. Vijay B. Shenoy](http://www.physics.iisc.ac.in/~shenoy/), IISc Bengaluru** (January 2022 - Present) <br> _Project Assistant, IISc_
  * Currently working on studies to explore the phases of $\mathbb{Z}_2$ lattice gauge theory using quantum Monte Carlo methods.
  * Preliminary work involved studying the classical Ising model in 2D and extracting critical exponents to get acquainted with numerical methods.
  * Working with _C++_, _Python_. 


* **Research internship with [Dr. Anosh Joseph](https://web.iisermohali.ac.in/Faculty/anoshjoseph/), IISER Mohali** (April 2021 - August 2021) <br> _Research Intern_ 
  * The research project involved the study of numerical methods to get around the "sign problem" plaguing Lattice QCD and condensed matter systems. The project involved attacking the sign problem via the following methods
    * _Complex Lagevin method_: Based on stochastic quantization of the fields. The field configuration is evolved according to a SDE and its equilibrium configuration is chosen as the sampling configuration. 
    * _Lefschetz Thimble method_: new manifolds, equivalent to the original domain of integration, are found in the complexified space, along which the imaginary part of the action is constant and, therefore, the integral is (mostly) real.
  * Since both methods rely on complexifying the fields, we also investigated the similarities and differences between the two.
  * Worked with _Python_, _Mathematica_.
  
  [Project Report](https://web.iisermohali.ac.in/Faculty/anoshjoseph/internships/2021/report_2021_Kunal_Verma.pdf): Numerical Methods for Evading the Sign Problem:
A Primer on Complex Langevin and Lefschetz Thimble Methods
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
