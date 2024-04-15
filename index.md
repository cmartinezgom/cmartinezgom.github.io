---
layout: archive
permalink: /
title: "Latest Posts"
image: bannertest.png
---

<div class="page__hero--overlay" style="background-image: url({{ page.image | relative_url }});"></div>

# ¡Bienvenido a mi blog!

Aquí encontrarás las últimas publicaciones sobre mis proyectos, ideas y todo lo que estoy explorando. ¡Espero que lo disfrutes!

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
