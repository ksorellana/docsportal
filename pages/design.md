---
layout: page
show_meta: false
title: "Información para Curadores"
subheadline: "Digitalización y Manejo de Colecciones"
teaser: "Documentación para curadores, enfocada en la digitalización y manejo de datos de colecciones biológicas.
header:
   image_fullwidth: "header_pluma.jpg"
permalink: "/curadores/"
---
<ul>
    {% for post in site.categories.curadores %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
