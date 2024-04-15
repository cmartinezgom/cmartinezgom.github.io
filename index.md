---
layout: archive
title: "Carlos Martínez"
image: bannertest.png
---

<div class="page__hero--overlay" style="background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url({{ page.image | relative_url }});"></div>

# ¡Hola, soy Carlos Martínez!

Soy un ingeniero de software apasionado por el desarrollo web y la inteligencia artificial. Aquí encontrarás las últimas publicaciones sobre mis proyectos, ideas y todo lo que estoy explorando. ¡Espero que lo disfrutes!

## 🌟 Destacados

Aquí puedes destacar algunos de tus posts o proyectos. Por ejemplo:

- Proyecto 1
- Proyecto 2
- Proyecto 3

## 📚 Blog

Aquí puedes encontrar mis últimas publicaciones de blog.

## 🎓 Cursos

Aquí puedes encontrar los cursos que he creado o en los que he participado.

- Curso 1
- Curso 2
- Curso 3


<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
