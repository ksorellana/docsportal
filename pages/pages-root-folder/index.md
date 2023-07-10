---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
    image_fullwidth: "GuatemalaHeader2-01.jpg"
widget1:
  title: "Documentación Para Curadores"
  url: 'http://biodiversidadgt.github.io/docs/curadores/'
  image: Portal2.jpg
  text: 'Doucmentación actualizada para la digitalización y manejo de colecciones en el Portal de Biodiversidad de Guatemala.'
widget2:
  title: "Documentación para Usuarios"
  url: 'http://biodiversidadgt.github.io/docs/usuarios/'
  image: Mapas.jpg
  text: 'Doucmentación actualizada para la la búsqueda y uso de información en el Portal de Biodiversidad de Guatemala.'
  video: '<a href="#" data-reveal-id="videoModal"><img src="https://github.com/biodiversidadgt/docs/blob/gh-pages/images/Mapas.jpg?raw=true" width="302" height="182" alt=""/></a>'
widget3:
  title: "Comunidad del Portal de Biodiversidad"
  url: 'http://biodiversidadgt.github.io/docs/blog/'
  image: Mapas.jpg
  text: 'Blog acerca de las actividades de digitalización desde las colecciones guatemaltecas que integran la Comunidad del Portal de Biodiversidad de Guatemala.'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: https://biodiversidad.gt
  text: Ir al Portal de Biodiversidad de Guatemala ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
