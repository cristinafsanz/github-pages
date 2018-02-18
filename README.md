# Casos de uso de GitHub Pages
Este repositorio contiene los casos de uso que estoy probando para trabajar con <a href="https://pages.github.com/">GitHub Pages</a>.

Presenté una charla para contar este proyecto en Codemotion Madrid 2017. La he repetido en [Comunidad CODE](https://comunidadcode.com/) para que quede grabada, por si hay más gente interesada en verla: 
- [Charla en YouTube](https://www.youtube.com/watch?time_continue=1&v=VBKQIiTl8Bc).
- [Slides y guión](https://github.com/cristinafsanz/slides#comunidad-code).

Para saber más sobre GitHub y GitHub Pages puedes consultar [¿Cómo se utiliza Github pages?](https://developer.mozilla.org/es/docs/Learn/Using_Github_pages)

En otros repositorios he creado notas sobre [Git](https://github.com/cristinafsanz/notas-git) y [GitHub](https://github.com/cristinafsanz/mastering-github) por si ayudan :)

## Índice

* [Origen](#origen)
  * [master](#master)
  * [docs](#docs)
  * [gh-pages](#gh-pages)

* [Utilidades](#utilidades)
  * [Página web](#página-web)
  * [Blog](#blog)
  * [Portfolio](#portfolio)
  * [Presentación](#presentación)
  * [Tutorial](#tutorial)
  * [Curso](#curso)

* [Avanzado](#avanzado)
  * [Dominio propio](#dominio-propio)
  
* [HTML Preview](#html-preview)

* [Jotted](#jotted)

* [Otros casos de uso](#otros-casos-de-uso)


## Origen

Hay dos posibilidades para publicar con GitHub Pages, usar el `User site` y publicar en `username.github.io` o usar `Project sites` para publicar en cualquiera de los repositorios que tengas (`username.github.io/repository`).

Los casos de uso que voy a compartir son todos `Project Sites`, pero si alguien quiere usar el `User Site` tiene que saber que en este caso el origen para publicar el código puede ser sólo `master`.

Para los `Project Sites` puedes publicar tu código desde las ramas `master` o `gh-pages` o el directorio `/docs` en la rama `master`. Hasta agosto de 2016 sólo se podía publicar desde `gh-pages`.

Para habilitar GitHub Pages desde `master`, `gh-pages` o `/docs` (dentro de la rama master) hay que ir a la sección `Settings` del repositorio y elegir el origen que quieras.

Los pasos para publicar tu página web serían los mismos que para subir a GitHub + el último paso de habilitar GitHub Pages:

  ```
  # GitHub (en repo): Copiar la url en GitHub en botón "Clone or download": Clone with HTTPS

  Ex. https://github.com/user/repository-name.git

  # En el terminal (local)

  git clone https://github.com/user/repository-name.git

  cd repository-name

  # Se añade todo el contenido en esa carpeta y se sube a GitHub

  git add . (si quieres añadir todo)

  git commit -m "Mensaje para el commit"

  git push origin master (si estás en la rama master)

  # Comprobación en GitHub

  https://github.com/user/repository-name

  # Habilitar GitHub Pages desde la pestaña "Settings"

  # Comprobar que está publicado

  https://user.github.io/repository-name

  ```

### master

Se publica el código que tienes alojado en la rama master.

* Repositorio de GitHub: https://github.com/cristinafsanz/melies-origen.

* Cómo se hizo (README): https://github.com/cristinafsanz/melies-origen.

* Resultado: https://cristinafsanz.github.io/melies-origen/.

### docs

Cuando queremos publicar el código de un subdirectorio del repositorio, ya sea documentación o ficheros de producción que se generan a partir del código de master.

* Repositorio de GitHub: https://github.com/cristinafsanz/melies-hugo.

* Cómo se hizo (README): https://github.com/cristinafsanz/melies-hugo.

* Resultado: https://cristinafsanz.github.io/melies-hugo/.

Para generar el código web se puede usar pre-commit y automatizarlo para que se genere siempre que se ejecute un commit. Un ejemplo se puede ver en el [README del blog de Hugo](https://github.com/cristinafsanz/melies-hugo#automizar-generación-de-ficheros-de-salida).

### gh-pages

Cuando no queremos que el código generado o la documentación esté en la misma rama que el resto del código.

Un ejemplo se explica en la charla <a href="https://www.youtube.com/watch?v=-MXVtFwS6Gw">Cómo desplegar tus proyectos Open Source</a> de <a href="https://twitter.com/laux_es">Ángel M Miguel</a>.

* Repositorio de GitHub (rama master): https://github.com/Angelmmiguel/rock-the-open-source.

* Repositorio de GitHub (rama gh-pages): https://github.com/Angelmmiguel/rock-the-open-source/tree/gh-pages.

* Resultado: https://angelmmiguel.github.io/rock-the-open-source/.

#### Un mismo proyecto generado para master, docs y gh-pages

* master: https://github.com/cristinafsanz/vue-master.

* docs: https://github.com/cristinafsanz/vue-master-docs.

* gh-pages: https://github.com/cristinafsanz/vue-gh-pages.

* gh-pages usando npm gh-pages: https://github.com/cristinafsanz/vue-gh-pages-npm.

* gh-pages con Travis: https://github.com/cristinafsanz/vue-gh-pages-travis.


## Utilidades

### Página web

* Repositorio de GitHub: https://github.com/cristinafsanz/alcelavistaytevimadrid.

* Resultado: http://cristinafsanz.github.io/alcelavistaytevimadrid/.

### Blog

* Repositorio de GitHub: https://github.com/cristinafsanz/melies-hugo.

* Resultado: https://melies-hugo.js.org/.

### Portfolio

* Repositorio de GitHub: https://github.com/cristinafsanz/projects.

* Resultado: http://cristinafsanz.github.io/projects/project/.

### Presentación

* Repositorio de GitHub: https://github.com/cristinafsanz/melies-origen.

* Resultado: https://cristinafsanz.github.io/melies-origen/.

### Tutorial

* Repositorio de GitHub: https://github.com/cristinafsanz/vuejs-primeros-pasos/tree/master/libro-vue.

* Resultado: https://cristinafsanz.github.io/vuejs-primeros-pasos/libro-vue/capitulo1/example-vue/.

### Curso

* Repositorio de GitHub: https://github.com/cristinafsanz/JavaScript30.

## Avanzado

### Dominio propio

* Repositorio de GitHub: https://github.com/cristinafsanz/melies-hugo.

* Cómo se hizo: https://github.com/cristinafsanz/melies-hugo#cambiar-dominio-de-github-pages.

* Resultado: https://melies-hugo.js.org/.

## HTML Preview:

Para poder ver el resultado si un repositorio de GitHub no tiene GitHub Pages habilitado.

* Repositorio GitHub: https://github.com/htmlpreview/htmlpreview.github.com.

* Página para visualizar el resultado: http://htmlpreview.github.io/.

Ejemplo:

* Animaciones CSS: https://github.com/nucliweb/AnimacionesCSS-EscuelaIT/tree/master/dia1/01.

* Resultado: http://htmlpreview.github.io/?https://github.com/nucliweb/AnimacionesCSS-EscuelaIT/blob/master/dia1/01/index.html.

## Jotted:

Puedes subir los ejercicios a GitHub y tener el código por un lado y la demo por otro, como en [Flexbox master](https://github.com/cristinafsanz/flexbox-master) o puedes utilizar una librería como [Jotted](https://github.com/ghinda/jotted) y tener una funcionalidad como JSFiddle pero alojada en GitHub, como [Flexbox jotted](https://github.com/cristinafsanz/flexbox-jotted).

## Otros casos de uso

### Documento cultura de empresa

* Libro blanco de Kaleidos: https://github.com/kaleidos/libro-blanco.

* Página web libro blanco: https://kaleidos.github.io/libro-blanco/.

### Información sobre comunidades:

* Geoinquietos: https://github.com/geoinquietos-org/geoinquietos-org.github.io.

* Página web Geoinquietos: http://geoinquietos.org/.

### Páginas web de conferencias:

* Conferenciaror: https://github.com/aprodeweb/conferenciaror.es.

* Página web conferenciaror: http://conferenciaror.es/.

* Frontfest: https://github.com/frontfest/frontfest.github.io.

* Página web Frontfest (compraron una plantilla estática y la desmenuzaron para adaptarla y que fuera más modular y fácil de editar, <a href="https://twitter.com/luisddm_">@luisddm</a>): http://frontfest.es/.

### Documentación de un framework:

* Phaser CE: https://github.com/photonstorm/phaser-ce.

* Documentación Phaser CE: https://photonstorm.github.io/phaser-ce/.

### Demos:

* Google closure-library: https://github.com/google/closure-library/tree/gh-pages/source/closure/goog/demos/editor.

* goog.editor Demo: https://google.github.io/closure-library/source/closure/goog/demos/editor/editor.html.

* Componente AngularJS: https://github.com/angular-ui-tree/angular-ui-tree.

* Ejemplos componente AngularJS: http://angular-ui-tree.github.io/angular-ui-tree/#/basic-example.

### Explicaciones con Demo grabada:

* Repositorio GitHub (rama gh-pages): https://github.com/Angelmmiguel/svgi/tree/gh-pages.

* Herramienta de inspección SVG: https://angelmmiguel.github.io/svgi/.

* Herramienta para grabación terminal: https://github.com/asciinema/asciinema.

### Preview tema para editores:

* Tema New Moon: https://github.com/taniarascia/new-moon.

* Preview resultado tema: https://taniarascia.github.io/new-moon/.

### Tutoriales:

* Código GitHub: https://github.com/rogerdudler/git-guide.

* Guía de git: http://rogerdudler.github.io/git-guide.

### Talleres:

* Código GitHub: https://github.com/delapuente/pwa-workshop.

* Taller (GitBook): https://delapuente.github.io/pwa-workshop/es/.

### Visualizaciones:

* Código GitHub: https://github.com/waapi/tool-transforms.

* Ejemplo visual: https://waapi.github.io/tool-transforms/.

### Presentaciones con sistema basado en CSS:

* Código GitHub: https://github.com/LeaVerou/talks.

* Ejemplo charla: https://leaverou.github.io/talks/mavo-talk/#.

* Sistema basado en CSS para presentaciones: https://github.com/LeaVerou/CSSS.

### Arte:

* Código GitHub: https://github.com/yiwenl/Sketches.

* Sketches: http://yiwenl.github.io/Sketches/.

### Experimentos WebVR:

* Código GitHub: https://github.com/nikgraf/webvr-experiments.

* Demo Bosque: https://nikgraf.github.io/webvr-experiments/HelloWorld/v3/.

* Demo Star wars: https://nikgraf.github.io/webvr-experiments/Animation/v2/.
