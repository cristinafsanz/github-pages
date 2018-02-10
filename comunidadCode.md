# Guión charla "Ilusionismo con GitHub Pages" en [Comunidad CODE](https://comunidadcode.com/)

## Introducción

### Estructura de la charla

- Para qué uso GitHub y GitHub Pages actualmente.

- Qué es, cómo funciona y algunos casos de uso.

- Notas adicionales a la charla.

- Preguntas de los asistentes a la charla.

### Un caso de uso para hoy

- Hacer un guión de una charla, como este fichero markdown: https://cristinafsanz.github.io/github-pages/comunidadCode.

### Toma notas de todo

- [Recomendación de Diana Hernández](https://twitter.com/IfThenElse__/status/960117304456564736).

- [Artículo "Take notes on everything"](https://dev.to/maxwell_dev/takes-notes-on-everything-3io).

    - Un conjunto de ficheros en markdown con notas de libros, artículos de blog o lo que sea que quiere tener para después: reglas de sintaxis, definiciones, trucos, ideas, frases, resúmenes...

    - Sirve como referencia para cuando tengas que volver a consultarlo (y también para otros al ser un repositorio público).

- [Repo Max Antonucci](https://github.com/maxx1128/Webdev-Study-Notes).

### Para qué estoy usando GitHub

- A partir de ideas de repositorios de gente que sigo en GitHub: [Personal Goals de Una Kravets](https://una.im/personal-goals-guide/), [setup de Tania Rascia](https://github.com/taniarascia/setup), [charla de Bash Jorge Aznar](https://gist.github.com/jorgeatgu/6b1f9bdf8ae9b02ad69d2f7bd039aac9#automatizaci%C3%B3n-con-gulp-y-bash), [repositorio charla Vue Jose Dongil](https://github.com/jdonsan/charla-aprendiendo-vuejs).

- Organización semanal / objetivos anuales: [Personal Goals](https://github.com/cristinafsanz/personal-goals).

- Configuraciones desarrollo (extensiones editor, Chrome, scripts, terminal...): [Setup](https://github.com/cristinafsanz/setup).

- Notas charla: [Vue primeros pasos](https://github.com/cristinafsanz/vuejs-primeros-pasos).

- Demo, código y notas de curso/manual: [Libro Vue](https://github.com/cristinafsanz/vuejs-primeros-pasos/blob/master/libro-vue/README.md).
  
    - [Notas](https://github.com/cristinafsanz/vuejs-primeros-pasos/blob/master/libro-vue/README.md#cap%C3%ADtulo-4-creando-componentes).

    - [Demo](https://cristinafsanz.github.io/vuejs-primeros-pasos/libro-vue/capitulo4/).

    - [Código](https://github.com/cristinafsanz/vuejs-primeros-pasos/tree/master/libro-vue/capitulo4).

- Pruebas: [Vuelidate](https://github.com/cristinafsanz/vuejs-primeros-pasos/blob/master/vue-playground/phone-formatting/vuelidate-example/README.md).

    - [Demo](https://cristinafsanz.github.io/vuejs-primeros-pasos/vue-playground/phone-formatting/vuelidate-example/dist/).

    - [Código](https://github.com/cristinafsanz/vuejs-primeros-pasos/tree/master/vue-playground/phone-formatting/vuelidate-example/src).

### Documentación con Markdown

- [¿Qué es?](https://dev.to/kazz/boost-your-productivity-using-markdown-1be)

- [Extensión de VSCode para ver cómo queda antes de subir a GitHub](https://marketplace.visualstudio.com/items?itemName=hnw.vscode-auto-open-markdown-preview).

### Pendiente: Mejor organización para notas y tutoriales

- Ejemplo [e-journal](https://github.com/elenatorro/e-journal) de Elena Torró.

    - Estructura en el fichero INDEX. 3 niveles en carpetas: Curso, Lección y Actividades.

    - Calendario para mostrar progreso.

- [Learning-Tracker](https://github.com/elena-in-code/Learning-Tracker) de Elena Moral. Basado en el de [Syk Houdeib](https://github.com/Syknapse/My-Learning-Tracker).

- [Guías, tutoriales y snippets](https://github.com/taniarascia/guides) de Tania Rascia.

## Ilusionismo con GitHub Pages

Nota inicial: Georges Méliès podría haber sido programador por su gran perseverancia: 

- Libro ["Vida y obra de un pionero del cine / Georges Méliès"](http://www.madrid.org/biblio_publicas/cgi-bin/abnetopac?TITN=999193#absysNET) en bibliotecas de la Comunidad de Madrid.

- [Slides compartir](https://cristinafsanz.github.io/slides/github-pages/#slide=1).

- [Slides en local (con gifs)](file:///Users/cristinafernandez/Others/slides/codemotion2017/index.html).

## Notas adicionales a la charla

- Pasos para publicar tu experimento:

    ```

    # GitHub (en repo): Copiar la url en GitHub en botón "Clone or download": Clone with HTTPS

    Ex. git@github.com/user/repository-name.git

    # En el terminal (local)

    git clone git@github.com/user/repository-name.git

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

- Para edición de algún fichero en concreto lo puedes hacer desde la aplicación web.

- [1 proyecto publicado de 5 formas](https://cristinafsanz.github.io/slides/github-pages/#slide=22) (la última descubierta después de la charla):

    - [Publicar en gh-pages con npm](https://github.com/cristinafsanz/vue-gh-pages-npm).





