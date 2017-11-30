# Aterrizaje-Lunar
Proyecto de aterrizaje lunar

## Paso 1: diseño de imágenes de fondo.
En primer lugar, he buscado imágenes de libre distribución sobre la luna y el universo y las he modelado con Photoshop para crear el fondo de pantalla. 

También he buscado una imágen de nave y la he recortado para poder usarla en la web.

## Paso 2: codificación del html y css.
El siguiente paso ha consistido en crear tantos html como pantallas accesibles desde un menú desplegable. En ellos, he ocultado y mostrado elementos acordes a las pantallas a las cuales se va accediendo.

Los estilos de dichos html están codificados en dos css, uno, utilizado para dispositivos móviles (en orientación vertical) y otro utilizado para  ordenadores o dispositivos con mayor definición de pantalla. 

En cada html está codificada una media query para identificar, dependiendo de la pantalla del dispositivo, a que hoja de estilos acceder, con lo cual conseguimos un diseño paralelo que se diferencia en el tamaño de los elementos y su posición en pantalla: cabaceras, desplegable, tabla, nave...

Dado lo anterior, tenemos tan solo, en nuestro caso, 5 ficheros html: index, como_jugar, nueva_partida, pause y reanudar.

## Paso 3: comprobación de media query.
Para comprobar la funcionalidad del media query, he copiado los archivos y ejecutado los html en un dipositivo móvil (bq Aquaris U lite en mi caso), para comprobar la redimensión de los elementos acorde a la resolución de pantalla.

## Paso 4: paleta de colores.
Los colores del html, los he ido comprobando desde la web [htmlcolordes](http://htmlcolorcodes.com/es/). Los colores que he escogido son los siguientes:

![Color 1](/img/color1.PNG).

![Color 2](/img/color2.PNG).

![Color 3](/img/color3.PNG).

![Color 4](/img/color4.PNG).

También he usado los colores por defecto: red, grey, white.

## Paso 5: crear repositorio GitHub.
He creado el repositorio GitHub con todos los archivos incluidos.

## Paso 6: validar el HTML.
Para 
Una vez establecidos todos los archivos, he validado el html. Para ello, he copiado el enlace del html de GitHub y lo he añadido a [RawGit](https://rawgit.com) para obtener un enlace. Mediante dicho enlace, me he dirigido a la web [validador w3](https://validator.w3.org) y he copiado allí el enlace.

## Paso 7: corrección de html.
Tras la primera validación me surgieron los siguientes errores:

![Errores](/img/errores.PNG).

La corrección de dichos errores consistía en eliminar los saltos de página entre los elementos de la lista y añadir un indicador a los elementos asociados al archivo css en los que establecí un margen entre elementos.

Tras la corrección de dichos errores, al volver a validar:

![Validación](/img/validación.PNG).

## Paso 8: Creación del README.md.
Por último, he creado el presente fichero README en el repositorio con los detalles de los pasos que he seguido para llevar a cabo la tarea. 

## Dirección URL.
Mi web es: [SwitchPlay](https://github.com/Pimpollo21/Tarea02-Parte-2/blob/master/SwitchPlay2.html ).
(La dirección de RawGit es: https://rawgit.com/Pimpollo21/Tarea02-Parte-2/master/SwitchPlay2.html )
