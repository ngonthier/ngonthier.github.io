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
* Ph.D in Signal and Image Processing, Paris-Saclay University, March 2021
  * Transfer learning of convolutional neural networks for texture synthesis and visual recognition in artistic images
* MEng in Data & Decision Sciences, ISAE-Supaero, 2017
* MSc in Stastistic, Université Paul Sabatier, 2017

Work experience
======
* Summer 2015: PostDoctoral Researcher Assistant
  * ENPC
  * Duties included: Tagging issues
  * Supervisor: Mathieu Aubry

* October 2017 - March 2021: PhD Student at Télécom Paris
  * Télécom Paris
  * Université Paris-Saclay
  * Supervisor: Yann Gousseau, Saïd Ladjal and Olivier Bonfait

Interests
======
* Machine Learning
  * Deep learning
* Image Processing
* Art History
* Digital Humanities

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
