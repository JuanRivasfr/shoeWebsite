# Video de referencia

<iframe width="560" height="315" src="https://www.youtube.com/embed/oWmOqxIanjk?si=5-d7lzG1Y7dDdOUq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

HTML
<nav> : Etiqueta que representa la seccion de una pagina, la cual sirve para proporcionar los enlaces de navegacion, ya sea en la misma pagina o hacia otra pagina
<header> : ES diferente al head, va dentro de la pagina representando la parte superior de esta
<head> : Representa la parte superior de la pagina, se puede interpretar como el encabezado
<alt> : No es una etiqueta, es una propiedad que puede ir dentro de img, el texto o valor que pongamos en su interior remplazara la imagen en caso que esta no cargue correctamente
<ul> : Se usa para crear una lista desordenada de elementos
<li> : Declara uno de los elementos de una lista
<form> : Se usa para una seccion sobre la cual el usuario puede enviar datos al servidor, la cual contiene controles interactivos
<i> : Crea una caja en linea, para introducir texto
<input> : Sirve para poner elementos input  en cualquier parte de un documento dentro de un formulario

CSS
display: 
Se usa para asginar que orientacion se usara, ya sea flex, grid, u otro

Flow layout: 
Es la orientacion normal de los items dentro de una pagina web, el orden normal es como si fuera un parrafo, un elemento tras otro

z-index: 
La propiedad z-index en CSS es utilizada para establecer la posición z (profundidad) de un elemento y sus descendientes a lo largo del eje z.
El valor que se asigna a z-index es un número, y determina el orden de apilamiento de los elementos. Un elemento con un z-index mayor se superpondrá a un elemento con un z-index menor. Si dos elementos tienen el mismo z-index, el orden en el que aparecen en el código HTML determinará cuál está encima.
Es importante tener en cuenta que z-index solo afecta a elementos que han sido posicionados de alguna manera (por ejemplo, con position: absolute, position: relative o position: fixed). Si no se especifica una posición, la propiedad z-index no tendrá ningún efecto.

position: relative;
La propiedad position: relative; en CSS se utiliza para posicionar un elemento de forma relativa con respecto a su posición normal en el flujo del documento. Cuando se aplica position: relative; a un elemento, aún ocupa su espacio original en el diseño, pero puedes ajustar su posición utilizando las propiedades top, right, bottom y left.
Aquí hay una breve descripción de cómo funciona position: relative; y cómo se usan las propiedades de posición:
top: Desplaza el elemento hacia arriba desde su posición normal en el flujo del documento. El valor puede ser positivo (hacia arriba) o negativo (hacia abajo).
right: Desplaza el elemento hacia la derecha desde su posición normal en el flujo del documento. El valor puede ser positivo (hacia la derecha) o negativo (hacia la izquierda).
bottom: Desplaza el elemento hacia abajo desde su posición normal en el flujo del documento. El valor puede ser positivo (hacia abajo) o negativo (hacia arriba).
left: Desplaza el elemento hacia la izquierda desde su posición normal en el flujo del documento. El valor puede ser positivo (hacia la izquierda) o negativo (hacia la derecha).
Al utilizar position: relative; sin especificar valores para top, right, bottom o left, el elemento se mantiene en su posición original, pero puedes ajustar su posición utilizando estas propiedades según sea necesario. Es común usar position: relative; como base para posicionar elementos secundarios de forma relativa con respecto a su contenedor.

max-width
La propiedad max-width en CSS se utiliza para establecer la anchura máxima de un elemento. En el caso de max-width: 1150px;, significa que el elemento no debe tener un ancho superior a 1150 píxeles.
Esta propiedad es especialmente útil en diseño web responsivo. Al limitar la anchura máxima de un elemento, puedes asegurarte de que no se extienda más allá de cierto límite incluso si el contenedor que lo rodea es más ancho.

margin: 0 auto;:
Además, la propiedad margin: 0 auto; se utiliza para centrar el contenedor horizontalmente. Esto es una técnica común para diseñar diseños responsivo

list-style-type: none;
La propiedad list-style-type: none; en CSS se utiliza para quitar los marcadores o viñetas de una lista (<ul> o <ol>). Esto es comúnmente utilizado cuando se desea diseñar una lista sin los puntos o números predeterminados que generalmente se muestran por defecto.

::placeholder
La pseudo-clase ::placeholder en CSS se utiliza para seleccionar y estilizar el texto de marcador de posición (placeholder) en un elemento de formulario. El texto de marcador de posición es el texto que aparece dentro de un campo de entrada antes de que se ingrese algún valor.

