---
layout: archive
title: "The Peazant Perspective"
permalink: /posts/
author_profile: true
header:
  overlay_color: "#000"
  overlay_filter: "0.4"
  overlay_image: /assets/images/blog.jpg
excerpt: "Thoughts on world events, cinema, culture, and my overall perspective on the craziness of life. It's time that the blog era made a comeback."
---

<div class="archive__subtitle">
  🎬 Cinema & Culture
</div>

<div class="grid__wrapper">
  {% for post in site.categories.Movies %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>

<div style="clear: both;"></div>
<hr>

<div class="archive__subtitle">
  📊 Economics & Data
</div>

<div class="grid__wrapper">
  {% for post in site.categories.Economics %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>