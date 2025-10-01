---
title: Zhengjie Zhou | Temple University
layout: home-with-sidebar  # Changed this line
group: home
description: "Research lab led by Dr. Zhengjie Zhou at Temple University. Focus areas: nanomedicine, vascular biology, ARDS, lung injury, pulmonary diseases."
url: "https://zhouzlab.github.io"
keywords: "Zhengjie Zhou, zhengjie zhou, Zhou Lab, zhou lab, Temple University, nanomedicine, vascular biology, ARDS, lung injury, pulmonary diseases"
author: "Zhengjie Zhou"
google_site_verification: "google3f8e48e801db6af3"
---

# Welcome to the Zhou Lab
###### Welcome to the Zhou Lab at the Lewis Katz School of Medicine at Temple University.  We are committed to the cutting-edge cell biology and nanomedicine research. We are driven by a passion for discovery at the intersection of nanomedicine, vascular biology, and pulmonary research. Our mission is to develop innovative, cell-targeted therapies to treat a wide range of lung diseases.


###### Our lab combines advanced drug delivery technologies, molecular biology, and interdisciplinary collaboration to uncover the mechanisms of disease and pioneer new treatment strategies. We aim to translate our discoveries into real-world solutions that improve lung health and patient outcomes.


###### Explore our research, meet the team, and learn more about our journey to shape the future of lung-targeted nanomedicine.


###### Our lab is located in the Medical Education & Research Building (Floor 11) on the Medical Campus of Temple University.

---

### What's new with us?

{% for post in site.posts limit:3 %}
_{{ post.date | date: "%-m-%-d-%Y" }}_ &nbsp; &nbsp; **{{ post.title }}** <br>
{{ post.content | replace: '<a', '[[a' | replace: '</a>', '[[/a]]' | strip_html | replace: '[[a', '<a' | replace: '[[/a]]', '</a>' | truncatewords: 50 }}
{% endfor %}



_Check [here](https://zhouzlab.github.io/news/) for more updates from the Zhou Lab_
