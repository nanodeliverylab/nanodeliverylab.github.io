---
layout: archive
title: "Research themes"
permalink: /research/
author_profile: true
---
{% include base_path %}

<p align= "justify">
  
Our lab is particularly focused on the study of the <strong>Protein Corona</strong>. The Protein Corona is a biomolecular layer that adsorb on nanoparticles upon contact with biological fluids (e.g. blood, serum and plasma) and strongly modifies their chemical-physical properties. As the Protein Corona represents a molecular interface that mediates the interactions among nanoparticles and living systems, it affects manifold biological processes at different scales and thus has a key-role for the effective clinical translation of nanomedicines.
Basically, we study the involvement and impact of the Protein Corona on each of the following research areas:<br><br>
  
<div class="grid">
  <div class="wrapper">
    {% for post in site.research %}
      {% include archive-single-proj.html type="grid" %}
    {% endfor %}
  </div>
</div>
