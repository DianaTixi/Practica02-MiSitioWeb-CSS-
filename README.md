# Practica02-MiSitioWeb-CSS-
Utilización de estilos CSS

1. Al finalizar la práctica se debe validar todas las páginas HTML y hojas de estilos CSS creadas usando el W3C Validator. 
Paginas HTML
Pagina index.


Pagina Piedra.html


Pagina CamaraS.html


Pagina PrisioneroA.html

Pagina Caliz.html


Pagina OrdenF.html

Pagina MisterioP.html

Pagina Reliquias1.html

Pagina Reliquias2.html


Pagina Formulario.html

Archivos CSS
Pagina principal.css








CSS Dos Columnas

CSS Tres Columnas 


CSS Formulario



2. Luego, se debe crear el archivo README del repositorio de GitHub. 
Se creó el archivo readme y se encuentra en el repositorio3. Generar informe de los resultados en el formato de prácticas. Debe incluir:
a. El desarrollo de cada uno de los puntos antes descritos así como las reglas CSS utilizadas para resolver cada punto.
1. Desarrollo de la Pagina Principal
• Configuracion general para la pagina principal

- Etiquetas para establecer la estructura general por cada parte
Padding: establece el espacio de relleno 
Margin: establece el margen que va a tener este puede ser (margin-top: margen superior) (margin-left: margen izquierdo) (margin-right: margen derecho) (margin-bottom: magen inferior)
Height: Sirve para establecer la altura
Width: Sirve para establecer el ancho 
Float: sirve para alinear un elemento ya sea a la izquierda o derecha

- Estructura de los estilos en la pagina principal

 

-Estilos aplicados en el header

 
Como se puede apreciar se utilizó una estructura de caja 
Los estilos aplicados en ellos son los siguientes:
Position: definimos que posición va a tener los elementos
Heigth: define la altura que va a tener esa caja
Wigth: sirve para definir el ancho de la caja o el elemento
Float: sirve para alinear el elemento ya sea izquierda o derecha
Left: sirve para posicionar al elemento en una distancia desde la izquierda
Padding: sirve para definir el espacio de relleno



 









- Estilo aplicado en el nav




Las etiquetas aplicas son:
Heigth: define la altura que va a tener esa caja
Margin: (margin-bottom: magen inferior) define el margen inferior 
Background: moz-linear-gradiente(top, color,color): sirve para el degrade de colores en este caso sería el degrade superior
Background: webkit-linear-gradiente(top, color,color): sirve para el degrade de colores en este caso sería el degrado inferior 





A su vez se aplica pseudo-clases para todas las etiquetas a que estén dentro de la etiqueta nav
Nav a:hover :  permite especificar el aspecto del elemento sobre el que se encuentra el ratón 
Nav a:link : define estilos para todas las etiquetas link
Nav a:visited: define estilos para todas las etiquetas “a” donde el usuario accedió

Nota: la estructura de nav se encuentra en todas las páginas del sitio web

- Para el contenido del sitio web se utilizó la siguiente estructura
















Como se puede apreciar en la imagen se utilizó un selector tipo class, dado que el class se puede aplicar en varias etiquetas 


Se puede verificar que se utiliza etiquetas anteriormente definidas a excepción de:
Display Block : hace que el comportamiento del elemento sea como un bloque 

- Estructura para el footer o pie de pagina














Se utiliza cajas para un mejor acoplamiento de la posición esto que tiene varias imágenes entro del footer, se utiliza el selector class para definir los estilos que aplicara





















2. Desarrollo del estilo DosColumnas aplicado en una pagina HTML (Ejemplo: CalizF.html)
- Estructura HTML
































- Para el header y nav  se utilizó la misma estructura que la página principal 
- Se aplicó los siguientes estilo para queda etiqueta utilizando selectores de class o id

































Se utilizó una estructura de cajas para poder determinar su posición, en este caso todas las cajas 
Asside: se utilizó esta etiqueta para crear una la menu con ayuda de (float left) para que su ubicación sea a la izquierda de igual manera se estableció un ancho
.secciones: se define el contenido de la pagina, utilizamos la (float right) para que su posicion sea a la derecha 
Background : url : establecemos que va a tener un fondo en esas etiquetas 

3. 3. Desarrollo del estilo TresColumnas aplicado en una pagina HTML (Ejemplo: Reliquias2.html)
- Estructura HTML

































- Implementación 








La evidencia del correcto diseño de las páginas HTML usando CSS. Para lo cuál, se puede generar fotografías instantáneas (pantallazos). 
 


