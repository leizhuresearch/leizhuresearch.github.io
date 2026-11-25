---
layout: default
title: home
permalink: /
photo: # file name of your photo in assets/img/, for example lei_zhu.jpg
---

<div class="home">
  <aside class="home-sidebar">
    {% if page.photo %}
      <img class="home-photo" src="{{ page.photo | prepend: '/assets/img/' | relative_url }}" alt="Photo of {{ site.first_name }} {{ site.last_name }}">
    {% else %}
      <div class="home-photo home-photo-placeholder" aria-hidden="true"><i class="fa-solid fa-user"></i></div>
    {% endif %}
    <h1 class="home-name">Dr. {{ site.first_name }} {{ site.last_name }}</h1>
    <p class="home-title">Postdoctoral Research Associate</p>
    <p class="home-affiliation">
      Department of Materials<br>
      University of Oxford, UK
    </p>
    <div class="home-links">{% social_links %}</div>
  </aside>

  <div class="home-main">
    <section class="home-section" markdown="1">

### About Me

I am a Postdoctoral Research Associate in the Department of Materials at the University of Oxford.

</section>

    <div class="home-columns">
      <section class="home-section" markdown="1">

### Research Interests

- Defects, interfaces and degradation in semiconductors and energy materials
- Mechanics of hybrid materials: nonlinear response, fracture and lattice anharmonicity
- Efficient learning strategies for developing machine-learning interatomic potentials
- Multiscale modelling with quantum-mechanical, QM/MM and machine-learning methods

</section>

      <section class="home-section" markdown="1">

### Education

- **PhD in Chemistry**<br>University College London, UK
- **MSc in Physics**<br>University College London, UK
- **MSc in Semiconductor Photonics and Engineering**<br>University of Sheffield, UK
- **BEng in Electronic Engineering**<br>Huaqiao University, China

</section>
    </div>

  </div>
</div>
