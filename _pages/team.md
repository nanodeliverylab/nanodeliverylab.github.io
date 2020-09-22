---
layout: archive
title: "Research Team"
permalink: /team/
author_profile: true
---

<hr-bold>
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

<hr-bold>
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

<hr-bold>
<h2>PhD students</h2>
<hr><br>
<div class="grid">
<div class="wrapper">
  {% for post in site.team %}
    {% if post.tags contains 'phd' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>
</div>

<hr-bold>
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

<hr-bold>
<h2>Former lab members</h2>

<hr><br>
&nbsp; &nbsp; Valentina Colapicchioni <br>
&nbsp; &nbsp; <h1>Stefano Coppola</h1> thesis title <br>
&nbsp; &nbsp; Giorgia La Barbera <br>
&nbsp; &nbsp; Alessandro Rossetta <br>
