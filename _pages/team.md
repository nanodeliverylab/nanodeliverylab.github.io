---
layout: archive
title: "Research Team"
permalink: /team/
author_profile: true
---

<br>
<h2>Principal Investigators</h2>
<hr><br>
<div class="grid">
<div class="wrapper">
  {% for post in site.team %}
    {% if post.tags contains 'PI' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>
</div>

<h2>Post-doctoral researchers</h2>
<hr><br>
<div class="grid">
<div class="wrapper">
  {% for post in site.team %}
    {% if post.tags contains 'post-doc' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
  </div>
  </div>

<h2>PhD students</h2>
<hr><br>
<div class="grid">
<div class="wrapper">
  {% for post in site.team %}
    {% if post.type contains 'phd' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>
</div>

<h2>Internship students</h2>
<hr><br>
<div class="grid">
<div class="wrapper">
  {% for post in site.team %}
    {% if post.tags contains 'internship' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>
</div>

<h2>Former lab members</h2>

<hr><br>
<strong>Laura Scarpati</strong>. Master's thesis. <em>Ruolo della corona proteica artificiale nella veicolazione di materiale genetico mediata da liposomi cationici.</em> 2020<br><br>
<strong>Benedetta Soccodato</strong>. Master's thesis. <em>Preparazione, caratterizzazione chimico-fisica e validazione in vitro di formulazioni liposomiali per la
veicolazione di Temozolomide nei tumori cerebrali.</em> 2019<br><br>
<strong>Valentina Colapicchioni</strong>. Ph.D. thesis. <em>title...</em> <br><br>
<strong>Stefano Coppola</strong>. Ph.D. thesis. <em>title...</em> <br><br>
<strong>Giorgia La Barbera</strong>. Master's thesis. <em>title...</em> <br><br>
<strong>Alessandro Rossetta</strong>. Master's thesis. <em>title...</em> <br><br>

<br>
<br>
  
<div style="text-align: center">
<img src='/images/FumettoLab.jpg' style='width: 50%'>
</div>
