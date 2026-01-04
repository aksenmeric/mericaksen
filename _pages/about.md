---
permalink: /
title: "About Me!"
layout: single
author_profile: true
---

I am a Ph.D. candidate in Civil Engineering at Stony Brook University, where I specialize in high-fidelity computational modeling of environmental fluid dynamics and renewable energy systems. I work within Dr. Ali Khosronejad’s research group and the U.S. Department of Energy–funded Atlantic Marine Energy Center (AMEC).

## Research focus and methods

My research expertise spans computational fluid dynamics, large-eddy simulations (LES), high-performance computing (HPC), and physics-guided machine learning for marine hydrokinetic (MHK) turbines and farms.

I develop site-specific, multi-scale numerical models that resolve turbulence and downscale them for accurate flow–structure interaction in tidal farms located in energetic tidal and riverine environments. These models integrate high-resolution geospatial data and field observations, and are used to improve resource characterization, feasibility assessment, and performance evaluation of pre-commercial MHK technologies.

## Upcoming focus

I am particularly interested in developing physics-informed machine learning models using data generated from high-fidelity numerical simulations, with applications to tidal farm design and optimization.

---

## Selected Research Portfolio

<div class="grid__wrapper">
  {% assign my_portfolio = site.portfolio | sort: "date" | reverse %}
  {% for post in my_portfolio limit:2 %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>


