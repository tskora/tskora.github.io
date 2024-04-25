---
title: "Coarse-grained simulations of proteins and protein polymers"
excerpt: ""
collection: portfolio
---

Principal investigator: **Prof. Gregory A. Voth**, **Dr. Tamara C. Bidone**

We harness Brownian dynamics simulations of integrin coarse-grained models to gain insight into the pathway of integrin activation, which is impossible to trace with all-atom molecular dynamics simulations due to its slow nature. Furthermore, we parametrize bottom-up coarse-grained model of a microtubule based on all-atom molecular dynamics simulations and use it to quantify the differences in stability between microtubules with GDP vs. GTP nucleotide in exchangeable binding sites of tubulin monomers.

<ul>{% for post in site.publications reversed %}
  {% if post.research == "cg" %}
  {% include archive-single-cv.html %}
  {% endif %}
{% endfor %}</ul>
