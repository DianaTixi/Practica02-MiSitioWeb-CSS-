# Practica02-MiSitioWeb-CSS-
Utilización de estilos CSS

1. Al finalizar la práctica se debe validar todas las páginas HTML y hojas de estilos CSS creadas usando el W3C Validator. 
Paginas HTML
Pagina index.
![image](https://user-images.githubusercontent.com/52221275/80232388-6df0f100-861a-11ea-8a40-9d37862f8ce0.png)

Pagina Piedra.html
![image](https://user-images.githubusercontent.com/52221275/80232440-87923880-861a-11ea-8070-9ad6607bc76b.png)

Pagina CamaraS.html
![image](https://user-images.githubusercontent.com/52221275/80232496-9f69bc80-861a-11ea-98a8-042c4da7a152.png)

Pagina PrisioneroA.html
![image](https://user-images.githubusercontent.com/52221275/80232554-b6101380-861a-11ea-8f8b-c5952bd37665.png)
Pagina Caliz.html
![image](https://user-images.githubusercontent.com/52221275/80232554-b6101380-861a-11ea-8f8b-c5952bd37665.png)

Pagina OrdenF.html
![image](https://user-images.githubusercontent.com/52221275/80238982-feccca00-8624-11ea-8411-8e5ccd8e10eb.png) 
Pagina MisterioP.html
![image](https://user-images.githubusercontent.com/52221275/80239012-11470380-8625-11ea-91d1-d6ebb58b9591.png )

Pagina Reliquias1.html
![image](https://user-images.githubusercontent.com/52221275/80239079-33408600-8625-11ea-8cb0-8a9f33e6b256.png)

Pagina Reliquias2.html
![image](https://user-images.githubusercontent.com/52221275/80239135-4a7f7380-8625-11ea-9342-8858e49df939.png)


Pagina Formulario.html
![image](https://user-images.githubusercontent.com/52221275/80239165-579c6280-8625-11ea-9f45-e74c4f4e3312.png)

Archivos CSS
Pagina principal.css
![image](https://user-images.githubusercontent.com/52221275/80239613-25d7cb80-8626-11ea-979c-dfb06628d66f.png)

CSS Dos Columnas
![image](https://user-images.githubusercontent.com/52221275/80239698-4d2e9880-8626-11ea-8cab-316792167900.png)

CSS Tres Columnas 
![image](https://user-images.githubusercontent.com/52221275/80239772-65061c80-8626-11ea-94c5-f02ea11e84e0.png)

CSS Formulario
![image](https://user-images.githubusercontent.com/52221275/80239837-7fd89100-8626-11ea-9c61-b7ad09ad3c5e.png)

2. Luego, se debe crear el archivo README del repositorio de GitHub. 
Se creó el archivo readme y se encuentra en el repositorio
3. Generar informe de los resultados en el formato de prácticas. Debe incluir:
a. El desarrollo de cada uno de los puntos antes descritos así como las reglas CSS utilizadas para resolver cada punto.
1. Desarrollo de la Pagina Principal
• Configuracion general para la pagina principal
![image](https://user-images.githubusercontent.com/52221275/80240194-12793000-8627-11ea-8b49-c639b5cc23fd.png)

- Etiquetas para establecer la estructura general por cada parte
Padding: establece el espacio de relleno 
Margin: establece el margen que va a tener este puede ser (margin-top: margen superior) (margin-left: margen izquierdo) (margin-right: margen derecho) (margin-bottom: magen inferior)
Height: Sirve para establecer la altura
Width: Sirve para establecer el ancho 
Float: sirve para alinear un elemento ya sea a la izquierda o derecha
![image](https://user-images.githubusercontent.com/52221275/80240273-2d4ba480-8627-11ea-8507-5dcada3286c5.png)

- Estructura de los estilos en la pagina principal
 

-Estilos aplicados en el header
![image](https://user-images.githubusercontent.com/52221275/80240278-30df2b80-8627-11ea-8d79-a545be8b51be.png)![image](https://user-images.githubusercontent.com/52221275/80240445-756ac700-8627-11ea-89c0-5b8c93da8b60.png)

Como se puede apreciar se utilizó una estructura de caja 
Los estilos aplicados en ellos son los siguientes:
Position: definimos que posición va a tener los elementos
Heigth: define la altura que va a tener esa caja
Wigth: sirve para definir el ancho de la caja o el elemento
Float: sirve para alinear el elemento ya sea izquierda o derecha
Left: sirve para posicionar al elemento en una distancia desde la izquierda
Padding: sirve para definir el espacio de relleno
![image](https://user-images.githubusercontent.com/52221275/80240455-7865b780-8627-11ea-993a-cd6a8dca197f.png)

- Estilo aplicado en el nav

 ![image](https://user-images.githubusercontent.com/52221275/80240513-8f0c0e80-8627-11ea-9df2-20011a817ea5.png)



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
 



