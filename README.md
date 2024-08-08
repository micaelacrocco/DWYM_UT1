# DWYM_UT1

TA1
Crear un documento HTML básico con una declaración <!DOCTYPE html>, una etiqueta de apertura y cierre <html>, una sección <head> que contenga una etiqueta <title>, y una sección <body>. Agregar un encabezado de nivel 1 (<h1>) y dos párrafos (<p>) dentro de la sección <body> del documento HTML.

TA2
En un nuevo documento HTML, crear una lista ordenada (<ol>) y una lista desordenada (<ul>) dentro de la sección <body>, cada una con tres elementos de lista (<li>).

TA3
En un nuevo documento HTML, agregar una imagen (<img>) dentro de la sección <body>, utilizando el atributo src para especificar la URL del archivo de imagen.

TA4
En un nuevo documento HTML, agregar tres hipervínculos (<a>) dentro de la sección <body>, cada uno apuntando a un sitio web diferente.

TA5
En un nuevo documento HTML, crear un formulario de registro utilizando los tags <form>, <label> e <input>. El formulario debe contar con un input de tipo submit para enviar la información, y un input de tipo reset para restablecer el formulario.

TA6
En un nuevo documento HTML, crear un formulario de encuesta con opciones de selección múltiple y botones de radio, utilizando para ello el tag <select> y el tipo de <input> correspondiente.

TA7
En un nuevo documento HTML, utilizar un tag apropiado para mostrar un video que se tenga a nivel local.

TA8
En un nuevo documento HTML, utilizar el tag <a> para tener 3 links, que lleven a Google, Facebook e Instagram.

TA9
En un nuevo documento HTML, utilizar el tag <iframe> para embeber YouTube dentro de su página web.

TA 10
En un nuevo documento HTML, crear 3 elementos. A estos 3 elementos se le debe agregar estilos, usando para cada uno de ellos un método diferente para agregar CSS, como se indica en la imagen de resultado a continuación.
Se pide usar sólamente selectores de tipo para este ejercicio al agregar estilos mediante los métodos externos e internos. También usar palabras clave para los colores (por ejemplo, "blue") en lugar de valores RGB o HEX.
 Los 3 elementos a estilar son:
•	div: un fondo rojo, texto blanco, un tamaño de fuente de 32px, alineación centrada y negrita
•	p: un fondo verde, texto blanco y un tamaño de fuente de 18px
•	button: un fondo naranja y un tamaño de fuente de 18px
Resultado esperado (sin tener en cuenta los textos) 

TA 11
Dado el siguiente HTML:
<!-- <!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Class and ID Selectors</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <p>Number 1 - I'm a class!</p>
    <div>Number 2 - I'm one ID.</div>
    <p>Number 3 - I'm a class, but cooler!</p>
    <div>Number 4 - I'm another ID.</div>
    <p>Number 5 - I'm a class!</p>
  </body>
</html> -->

Agregue un archivo CSS externo que, utilizando selectores de clase y de id, le permita cumplir con lo siguiente:
•	Todos los elementos impares: un fondo rojo claro/rosa, y una lista de fuentes que contenga Verdana y DejaVu Sans con sans-serif como alternativa 
•	El segundo elemento: texto azul y un tamaño de fuente de 36px 
•	El tercer elemento: además de los estilos para todos los elementos impares, agrega un tamaño de fuente de 24px 
•	El cuarto elemento: un fondo verde claro, un tamaño de fuente de 24px y negrita
Resultado esperado
 
Checklist
•	¿Los elementos p impares comparten una clase? 
•	¿Los elementos div pares tienen IDs únicos? 
•	¿El elemento número 3 tiene múltiples clases?

TA 12
Dado el siguiente HTML:
<!-- <!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grouping Selectors</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <button>Click Me!</button>
    <button>No, Click Me!</button>
  </body>
</html> -->

Agregar un archivo CSS externo que aplique estilos a los elementos de la siguiente manera:
•	El primer elemento: un fondo negro y texto blanco 
•	El segundo elemento: un fondo amarillo 
•	Ambos elementos: un tamaño de fuente de 28px y una lista de fuentes que contenga Helvetica y Times New Roman, con sans-serif como alternativa
La idea de este ejercicio es identificar qué reglas CSS se comparten entre ambos elementos, para poder combinar selectores y no repetir reglas y cuáles son únicas para cada elemento. Cada elemento debe tener un único selector de clase aplicado. 

Resultado esperado
 
Checklist
•	¿Cada elemento tiene un nombre de clase único? 
•	¿Usaste el selector de agrupamiento para los estilos que ambos elementos comparten? 
•	¿Hiciste reglas separadas para los estilos únicos de cada elemento?

TA 13
Dado el siguiente HTML:
<!-- <!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chaining Selectors</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <div>
      <img class="avatar proportioned" src="img1" alt="">
      <img class="avatar distorted" src="img2" alt="...>
    </div>
    <div>
      <img class="original proportioned" src="img1" alt="">
      <img class="original distorted" src="img2" alt="">
    </div>
  </body>
</html> -->

El propósito de este ejercicio es enfocarse en entender cómo combinar diferentes selectores, en lugar de simplemente agregar atributos.
Se tienen 2 imágenes (que deben ser proporcionadas por el alumno), las cuáles se quiere estilar. El objetivo aquí es combinar los selectores para ambos elementos, de modo que cada uno tenga un estilo único aplicado, a pesar de usar un selector de clase compartido. Por ejemplo, se quiere que un elemento que tiene tanto X como Y tenga un conjunto de estilos, mientras que un elemento con X y Z tiene un conjunto completamente diferente de estilos. 
 Las reglas CSS que necesitas agregar a cada elemento son:
•	Haz que el elemento con ambas clases avatar y proportioned tenga un ancho de 300px, luego dale una altura para que mantenga sus proporciones cuadradas originales. No hay que darle un valor en píxeles para la altura.
•	Haz que el elemento con ambas clases avatar y distorted tenga un ancho de 200 píxeles, luego haz que su altura sea el doble de su ancho. Para este caso, sí hay que usar un valor en píxeles para la altura.

Resultado esperado
 
Checklist
•	¿Combinaste correctamente los selectores de clase para cada regla? 
•	¿La imagen proporcionada mantiene sus proporciones cuadradas originales? 
•	¿La imagen distorsionada termina viéndose comprimida y, bueno, distorsionada?

TA 14
Dado el siguiente HTML:
<!-- <!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Descendant Combinator</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <div class="container">
      <p class="text">This should be styled.</p>
    </div>
    <p class="text">This should be unstyled.</p>
    <p class="text">This should be unstyled.</p>
    <div class="container">
      <p class="text">This should be styled.</p>
      <p class="text">This should be styled.</p>
    </div>
  </body>
</html> -->

El objetivo de este ejercicio es aplicar estilos a los elementos que son descendientes de otro elemento, dejando sin estilo los elementos que no son descendientes de ese elemento. Se pueden usar selectores de tipo o de clase para este ejercicio.
Concretamente, lo que se pide es:
•	Solo los elementos p que son descendientes del elemento div deben tener un fondo amarillo, texto rojo, un tamaño de fuente de 20px y alineación centrada
Resultado esperado:
 
TA 15
Dado el siguiente HTML:
<!-- <!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fix the Cascade</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <p class="para">I'm just a paragraph with extra bold text!</p>
    <p class="para small-para">I'm a smaller paragraph, also with extra bold text!</p>
 
    <button id="confirm-button" class="button confirm">Confirm</button>
    <button id="cancel-button" class="button cancel">Cancel</button>
 
    <div class="text">I'm a div with thin text!</div>
    <div class="text">I'm a div with thin text and a child div!
      <div class="text child">I'm a smaller child div with extra bold text.</div>
    </div>
  </body>
</html> -->

Dado el siguiente CSS:

body {
  font-family: Arial, Helvetica, sans-serif;
}
 .para,
.small-para {
  color: hsl(0, 0%, 0%);
  font-weight: 800;
}
.small-para {
  font-size: 14px;
  font-weight: 800;
}
 .para {
  font-size: 22px;
}
 .confirm {
  background: green;
  color: white;
  font-weight: bold;
} 
 .button {
  background-color: rgb(255, 255, 255);
  color: rgb(0, 0, 0);
  font-size: 20px;
}
 .child {
  color: rgb(0, 0, 0);
  font-weight: 800;
  font-size: 14px;
}
 
div.text {
  color: rgb(0, 0, 0);
  font-size: 22px;
  font-weight: 100;
}

Hay algunos elementos que tienen algún tipo de problema de especificidad o de orden de reglas en el archivo CSS proporcionado. 
Se pide descubrir qué problema está afectando a un elemento y cómo solucionarlo, de forma tal de alcanzar el resultado esperado. Se puede editar el archivo CSS agregando, eliminando o editando selectores para un bloque de declaraciones, o moviendo bloques de declaraciones. 
No se debe editar el archivo HTML ni ninguno de los estilos actuales en el CSS.
Resultado esperado
