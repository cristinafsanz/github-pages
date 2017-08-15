# Casos de uso de GitHub Pages
Este repositorio contiene los casos de uso que estoy probando para trabajar con <a href="https://pages.github.com/">GitHub Pages</a>. Si quieres aportar más ideas, puedes contactarme por twitter a <a href="https://twitter.com/cristinafsanz">@cristinafsanz</a>.

## Índice

* [Origen](#origen)
  * [master](#master)
  * [gh-pages](#gh-pages)
  * [docs](#docs)

* [Utilidades](#utilidades)
  * [Página web](#página-web)
  * [Blog](#blog)
  * [Portfolio](#portfolio)
  * [Presentación](#presentación)
  * [Tutorial](#tutorial)
  * [Curso](#curso)

* [Avanzado](#avanzado)
  * [Dominio propio](#dominio-propio)

* [Otros casos de uso](#otros-casos-de-uso)

* [HTML Preview](#html-preview)

## Origen

Hay dos posibilidades para publicar con GitHub Pages, usar el `User site` y publicar en `username.github.io` o usar `Project sites` para publicar en cualquiera de los repositorios que tengas (`username.github.io/repository`).

Los casos de uso que voy a compartir son todos `Project Sites`, pero si alguien quiere usar el `User Site` tiene que saber que en este caso el origen para publicar el código puede ser sólo `master`.

Para los `Project Sites` puedes publicar tu código desde las ramas `master` o `gh-pages` o el directorio `/docs` en la rama `master`. Hasta agosto de 2016 sólo se podía publicar desde `gh-pages` por lo que los ejemplos que he hecho hasta esa fecha son desde esa rama.

Para habilitar GitHub Pages desde `master` o `/docs` hay que ir a la sección `Settings` del repositorio. Desde `gh-pages` no hace falta, si no está habilitado para los orígenes anteriores y se sube código a esa rama, entonces se mostrará automáticamente.

### master

Para proyectos web con sólo html, css y JavaScript o proyectos que usen el generador estático Jekyll.

* Repositorio de GitHub: https://github.com/cristinafsanz/melies-origen.

* Cómo se hizo (README): https://github.com/cristinafsanz/melies-origen.

* Resultado: https://cristinafsanz.github.io/melies-origen/.

### gh-pages

Para proyectos web con sólo html, css y JavaScript o proyectos que usen el generador estático Jekyll.

Actualmente tiene más sentido usarlo para alojar el código web generado a partir de otro subido a master (por ejemplo proyecto con gulp o código de un generador estático).

Un ejemplo se explica en la charla <a href="https://www.youtube.com/watch?v=-MXVtFwS6Gw">Cómo desplegar tus proyectos Open Source</a> de <a href="https://twitter.com/laux_es">Ángel M Miguel</a>.

* Repositorio de GitHub (rama master): https://github.com/Angelmmiguel/rock-the-open-source.

* Repositorio de GitHub (rama gh-pages): https://github.com/Angelmmiguel/rock-the-open-source/tree/gh-pages.

* Resultado: https://angelmmiguel.github.io/rock-the-open-source/.

### docs

Para proyectos donde hay código fuente que no es web, pero a partir de él se genera el código web (como proyecto con gulp o código de un generador estático) o se añade documentación sobre un proyecto.

#### Proyecto generador estático

* Repositorio de GitHub: https://github.com/cristinafsanz/melies-hugo.

* Repositorio de GitHub (directorio /docs): https://github.com/cristinafsanz/melies-hugo/tree/master/docs.

* Cómo se hizo (README): https://github.com/cristinafsanz/melies-hugo.

* Resultado: https://melies-hugo.js.org/.

#### Proyecto Angular con gulp

* Repositorio de GitHub: https://github.com/cristinafsanz/angularjs-gulp-browserify-boilerplate.

* Cómo se hizo (README): https://github.com/cristinafsanz/angularjs-gulp-browserify-boilerplate.

* Resultado: https://cristinafsanz.github.io/angularjs-gulp-browserify-boilerplate/.

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

* Repositorio de GitHub: https://github.com/cristinafsanz/angular-crud.

* Resultado: https://cristinafsanz.github.io/angular-crud/index.html.

### Curso

* Repositorio de GitHub: https://github.com/cristinafsanz/JavaScript30.

## Avanzado

### Dominio propio

* Repositorio de GitHub: https://github.com/cristinafsanz/melies-hugo.

* Cómo se hizo: https://github.com/cristinafsanz/melies-hugo#cambiar-dominio-de-github-pages.

* Resultado: https://melies-hugo.js.org/.

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

## HTML Preview:

Para poder ver el resultado si un repositorio de GitHub no tiene GitHub Pages para alojar sus ficheros html.

* Repositorio GitHub: https://github.com/htmlpreview/htmlpreview.github.com.

* Página para visualizar el resultado: http://htmlpreview.github.io/.

Ejemplo:

* Animaciones CSS: https://github.com/nucliweb/AnimacionesCSS-EscuelaIT/tree/master/dia1/01.

* Resultado: http://htmlpreview.github.io/?https://github.com/nucliweb/AnimacionesCSS-EscuelaIT/blob/master/dia1/01/index.html.


