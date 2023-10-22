<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 10 

### Actividad: Propiedades de posicionamiento de CSS
Objetivo:

Aplicar las propiedades de posicionamiento de CSS para crear diferentes efectos de visualización.

Instrucciones:

- Crea un nuevo archivo HTML y CSS.
- En el archivo HTML, crea una estructura básica de página web con dos elementos div.
- En el archivo CSS, define las propiedades de visualización y posicionamiento de los elementos div.

Ejemplo:

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Ejemplo de posicionamiento de CSS</title>
  <style>
    .elemento-1 {
      position: absolute;
      top: 100px;
      left: 100px;
      background-color: red;
    }

    .elemento-2 {
      position: relative;
      top: 100px;
      left: 100px;
      background-color: green;
    }
  </style>
</head>
<body>
  <div class="elemento-1"></div>
  <div class="elemento-2"></div>
</body>
</html>
```

Este ejemplo muestra dos elementos div posicionados de forma absoluta y relativa, respectivamente. El elemento .elemento-1 se posiciona a 100 píxeles de la parte superior y izquierda de la ventana del navegador, mientras que el elemento .elemento-2 se posiciona a 100 píxeles de su posición original en el flujo normal del documento.

Preguntas:

1. ¿Cuál es la diferencia entre los valores position: absolute y position: relative?
2. ¿Cómo se puede usar la propiedad z-index para controlar el orden de apilamiento de los elementos posicionados?
3. ¿Cómo se puede usar la propiedad display para controlar cómo se muestra un elemento en una página web?

### Solucion

#### Codigo HTML

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Ejemplo de posicionamiento de CSS</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="elemento-1">Este es una prueba</div>
    <div class="elemento-2">Otra puebra</div>
    <div class="elemento-3">Un saludo primero</div>
    <div class="elemento-4">Ultima prueba</div>
</body>
</html>
```

#### Codigo CSS

```css
.elemento-1 {
    position: static;
    top: 100px;
    left: 100px;
    right: 100px;
    border-radius: 100px;
    display: inline-block;
    background-color: red;
    font-size: 60px;
    font-family: cursive;
  }

  .elemento-2 {
    position: absolute;
    top: 100px;
    left: 10px;
    background-color: green;
    font-size: 60px;
    border-radius: 100px;
    font-family: cursive;

  }
.elemento-3 {
    position: absolute;
    top: 200px;
    left: 10px;
    display: inline-block;
    background-color: rgb(38, 0, 255);
    font-size: 60px;
    border-radius: 100px;
    font-family: cursive;

  }

  .elemento-4 {
    position: fixed;
    top: 300px;
    left: 10px;
    background-color: rgb(255, 230, 0);
    font-size: 60px;
    border-radius: 100px;
    font-family: cursive;

  }
```

#### Preguntas

1. La posicion absolute hace que el elemento se posicione de forma absoluta, es decir, se coloca en una posición específica en la página, independientemente del flujo normal del documento.

Mientras que la posicion relative hace que  elemento se posicione de forma relativa, es decir, se desplaza desde su posición original en el flujo normal del documento.

2. La propiedad z-index de CSS especifica el orden de apilamiento de un elemento posicionado y sus descendientes. Cuando varios elementos se superponen, los elementos con mayor valor z-index cubren aquellos con menor valor.

El valor de z-index puede ser un número entero positivo o negativo. Un valor de z-index de 0 significa que el elemento se comporta de forma normal, siguiendo el flujo normal del documento, es decir, mientras el numero sea menor, sera el de menos posicion, por lo que se vera al fondo, y el de mayor valor es de los primeros en aparecer dependiendo de cuantos valores z-index existan.

3. La propiedad display de CSS determina cómo se muestra un elemento en una página web. Hay cuatro valores diferentes para la propiedad display, cada una funciona para algo especifico, por lo que se puede aplicar de forma creativa a la hora de un desarrollo web:

- block: El elemento se muestra como una caja de bloque, que ocupa toda la anchura de su contenedor y se muestra en una nueva línea.
- inline: El elemento se muestra como una caja de línea, que se muestra en la misma línea que el texto circundante.
- inline-block: El elemento se muestra como una caja de línea, pero puede tener una anchura y una altura definidas.
- none: El elemento no se muestra en la página web.








