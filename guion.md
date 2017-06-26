# Ilusionismo con GitHub Pages

## Presentación

Soy Cristina Fernández, desarrolladora front-end desde hace 2 años. Llevo un tiempo investigando formas de ir mejorando en mi trabajo. La más eficaz seguramente es aprender haciendo y en el caso de desarrollo front-end esto se traduce en hacer páginas web con HTML, CSS y JavaScript aplicando las tecnologías que aprendes.

## Portfolio web

De la misma forma que los diseñadores tienen un portfolio con sus diseños, los desarrolladores podemos tener un portfolio con nuestro código, aunque en el caso de los desarrolladores front-end también es importante mostrar el diseño web resultante. En la presentación os pongo un ejemplo de página web que agrupa diseños web inspiradores. Algo así podríamos tener nosotros para alojar nuestros diseños web experimentales, los que realizamos para aprender. La pregunta es, ¿dónde podemos alojar nuestros projectos en alguna plataforma para que tanto el código como la página web resultante puedan compartirse y consultarse? Me hacía esta pregunta cuando empecé como front-end y un día un compañero de trabajo habló de GitHub Pages y se me iluminó la bombilla.

## Presentación Cinematógrafo (1895)

Para que véais cómo me sentí tenemos que retroceder en el tiempo hasta el año 1895, cuando los hermanos Lumière presentaron el invento del cinematógrafo en una sala en París. Una de las películas proyectadas era la "Llegada de un tren a la estación de la Ciotat" que podéis ver en la presentación. 

Entre los asistentes se encontraba el ilusionista Georges Méliès, que quedó impresionado y quiso incorporar este invento a sus representaciones de magia. Al año siguiente empezó a realizar películas que incorporaban trucos de magia con un aparato de la competencia e hizo más de 500 películas hasta 1913. Entre ellas hizo "Viaje a la luna" en 1902.

## Mi GitHub (2016)

De la misma forma, aunque a menor escala, empecé yo con el "invento" de GitHub Pages, creándome repositorios para almacenar el código que fuera haciendo y también usando GitHub Pages para mostrar el resultado. En unos días subí una página web, creé mi portfolio y 2 blogs para probar el generador estático Jekyll.

## Git, GitHub y GitHub Pages

Para aquellos de vosotros que no sepan qué es GitHub Pages voy a explicar los sistemas en los que se basa. Voy a utilizar escenas de la película "Viaje a la luna" de Georges Méliès como analogía.

- Git: Es un sistema de control de versiones que permite almacenar los cambios que vas haciendo en tu código y poder volver a anteriores versiones. El código sería la cápsula, que inicialmente está en local.

- GitHub: Es una de las posibles plataformas para almacenar tu código de forma remota. GitHub sería la luna, que recibe el código con un impacto en el ojo.

- GitHub Pages: Es un servicio de GitHub que permite publicar la página web cuyo código alojas en GitHub. GItHub Pages es cómo se ve la luna una vez estás en ella.

## GitHub Pages

En la página oficial de GitHub Pages podéis encontrar información sobre cómo funciona. Yo os voy a explicar lo más importante, de nuevo a partir de películas hechas por Méliès.

## User site y Project Sites

Hay 2 formas de publicar una página web. Usar la url que te asignan por usuario de GitHub o usar un una url asociada a un repositorio dentro de GitHub. Se puede tener una única User site por cuenta y todas las Project Sites que quieras, una por repositorio.

## User site y Project Sites

Para crear una User site tienes que crear un repositorio con un nombre específico: username.github.io. Para cualquier otro nombre lo que creas es un Project Site.

Tanto para User site como para Project site puedes hacer lo siguiente para publicar tu página web:

- Crear el repositorio.

- Clonar el repositorio en local.

- Crear el código web.

- Subir el código a GitHub con Git.

## Project sites

Éstos serían algunos de los ejemplos de páginas web que he creado, hasta ahora todo Project sites.

## Habilitar GitHub Pages

Hay 3 formas de habilitar GitHub Pages en caso de Project Site. Para User site se usa el código de master solamente.

- Subir el código a la rama gh-pages. Esta opción era la única disponible hasta agosto 2016.

- Subir el código a master.

- Subir el código a master y usar la carpeta /docs dentro de master para publicar la página web.

Para las 2 últimas opciones se necesita habilitar GitHub Pages desde la pestaña de ajustes.

## Dominio personalizado

Puedes habilitar un dominio personalizado al que redireccionar desde la url asignada de GitHub Pages. Tienes que seguir las instrucciones del proveedor del dominio y poner el dominio asignado en la pestaña de ajustes, en Dominio personalizado. Esto crea un fichero CNAME en la raíz de donde se habilita GitHub Pages. También se podría crear directamente el fichero.

## Ejemplos de uso

Algunos ejemplos, además de subir una página web, puede ser subir una presentación como la que estoy mostrando hoy (que realmente es una página web con un JavaScript que hace la magia para cambiar de página y es un proyecto que se llama WebSlides) o un blog.

Para hacer un blog puedes usar un generador estático de los que aparecen en https://www.staticgen.com/. En GitHub se utiliza por defecto Jekyll pero quería probar otro. No sabía bien cual usar hasta que vi un generador estático que se llamaba Hugo y decidí usar éste. ¿Por qué? ¿Rapidez? ¿Facilidad de uso?

## Hugo

No, porque se llama igual que una película que hace un homenaje a Georges Méliès :)

## Gracias

Cualquier sugerencia sobre qué te gustaría saber más sobre GitHub Pages la puedes hacer en twitter en @cristinafsanz.
