---
layout: archive
title: "Collaborations"
permalink: /collaborations/
author_profile: true
---

Principal Investigators of the research groups working with us:

{% include base_path %}

<div class="grid">
  <div class="wrapper">
    {% for post in site.collaborations %}
      {% include archive-single-proj.html type="grid" %}
    {% endfor %}
  </div>
</div>
