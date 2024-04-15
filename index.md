---
layout: home
title: "Carlos Martínez"
image: bannertest.png
---


# ¡Hola, soy Carlos Martínez!

Soy un ingeniero de software apasionado por el desarrollo web y la inteligencia artificial. Aquí encontrarás las últimas publicaciones sobre mis proyectos, ideas y todo lo que estoy explorando. ¡Espero que lo disfrutes!

## 🌟 Destacados

Aquí puedes destacar algunos de tus posts o proyectos. Por ejemplo:

- Proyecto 1
- Proyecto 2
- Proyecto 3

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
