---
title: "Diffusion in crowded environments"
excerpt: ""
collection: portfolio
---

Principal investigator: **Dr. Svyatoslav Kondrat**

We harness Brownian dynamics simulations to reveal the generic effects of macromolecules’ properties, e.g., shape and activity, on the diffusion coefficients in cells.

<ul>{% for post in site.publications reversed %}
  {% if post.research == "diff" %}
  {% include archive-single-cv.html %}
  {% endif %}
{% endfor %}</ul>

One of my current aims is to develop a versatile software -- [``pyBrown``](https://tskora.github.io/pyBrown), for simulations of diffusion and reactions accounting for the hydrodynamic interactions. You can find the code [here](https://github.com/tskora/pyBrown), and its documentation [here](https://tskora.github.io/pyBrown).