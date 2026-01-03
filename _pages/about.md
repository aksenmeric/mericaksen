---
permalink: /
title: "About Me!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

About Me
I am a Ph.D. candidate in Civil Engineering at Stony Brook University, where I specialize in high-fidelity computational modeling of environmental fluid dynamics and renewable energy systems. I work within Dr. Ali Khosronejad’s group and the U.S. Department of Energy-funded Atlantic Marine Energy Center (AMEC, amec-us.org). 

Research focus and methods:
My research expertise spans computational fluid dynamics, large-eddy simulations, high-performance computing, and physics-guided machine learning for marine hydrokinetic (MHK) turbines and farms. 
I develop site-specific, multi-scale numerical models that resolve turbulence, and I downscale these models for accurate flow-structure interactions in tidal farms in energetic tidal and riverine environments, integrating high-resolution geospatial data and field observations. 
These models are used to improve resource characterization, feasibility assessment, and performance evaluation of pre-commercial MHK technologies. 

Upcoming focus:
I am particularly interested in developing physics-informed machine learning models using data from high-fidelity numerical models.

<hr />

## Selected Research Portfolio

{% include base_path %}

<div class="entries-list">
  {% for post in site.portfolio %}
    {% include archive-single.html %}
  {% endfor %}
</div>

<p style="margin-top:1rem;">
  <a class="btn btn--primary" href="{{ '/portfolio/' | relative_url }}">View full portfolio</a>
</p>


