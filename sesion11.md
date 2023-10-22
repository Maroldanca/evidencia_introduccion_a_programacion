<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 11 

## Actividad: Propiedades CSS, SeudoClases, SeudoElementos y Reglas @css

Crear un documento HTML y probar cada uno de los ejemplos de la sesión 11

### Solucion

#### Codigo html

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="Css.css">
</head>
<body>
    <h1>titulo de pruebas sesion 11</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Expedita quam sequi tempora totam repudiandae, dignissimos eos corrupti reiciendis ea porro! Animi, et modi? Atque dignissimos veniam minima, voluptatibus molestias nisi!</p>
</body>
</html>
```

#### Codigo css

```css

/* Tamaño y posicion */

body {
    width: 100%;
    height: 100vh;
    margin: 0;
    padding: 0;
  }
  
  h1 {
    width: 50%;
    height: 100px;
    margin: 10px auto;
    padding: 20px;
  }
  
  p {
    float: left;
    width: 50%;
    height: 100px;
    margin: 10px;
    padding: 20px;
  }

  /* Color y fondo */

  body {
    color: #000;
    background-color: #fff;
  }
  
  h1 {
    color: #fff;
    background-color: #000;
  }
  
  p {
    background-image: url(image.jpg); 
    background-repeat: repeat-y;
    background-position: center;
  }


  /* Fuente */

  body {
    font-family: sans-serif;
    font-size: 16px;
  }
  
  h1 {
    font-family: 'Times New Roman', serif;
    font-size: 24px;
    font-weight: bold;
  }
  
  p {
    font-style: italic;
    font-variant: small-caps;
  }

  /* Texto */
  
  h1 {
    text-align: center;
  }
  
  p {
    text-align: justify;
  }


  /* Bordes */

  body {
    border: 1px solid black;
  }
  
  h1 {
    border-width: 2px;
    border-style: dashed;
    border-color: red;
  }
  
  p {
    border-radius: 10px;
  } 
```

### Seudoclases y seudoelementos

#### Codigo html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="Css.css">
</head>
<body>
    <h1>titulo de pruebas sesion 11</h1>
    
    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Tempora odit, inventore possimus aut enim nihil pariatur ipsa quam deleniti reprehenderit, repudiandae esse ut quod, libero provident distinctio obcaecati cum maiores.</p>

    <a href="#">Enlace</a>

    <button>Boton de accion</button>

    <ul>
        <li>Manzanas</li>
        <li>Plátanos</li>
        <li>Naranjas</li>
        <li>Uvas</li>
      </ul>

      <select id="idioma" name="idioma">
        <option value="es">Español</option>
        <option value="en">Inglés</option>
        <option value="fr">Francés</option>
        <option value="de">Alemán</option>
        <option value="it">Italiano</option>
      </select>
      
</body>
</html>
```

#### Codigo css

```css
/* Color de accion */

a {
    color: blue;
  }
  
  a:link {
    background-color: red;
  }
  
  a:active {
    background-color: green;
  }

/* Color de fondo de un parrafo */
  p {
    background-color: white;
  }
  
  p:hover {
    background-color: gray;
  }

  /* Activar un botón cuando el usuario hace clic en él: */
  button {
    cursor: pointer;
    background-color: blue;
  }
  
  button:active {
    background-color: red;
  }

  /* Deshabilitar un botón: */
  button {
    cursor: pointer;
    background-color: blue;
  }
  
  button:disabled {
    cursor: not-allowed;
    background-color: gray;
  }

  /* Activar un enlace cuando el usuario hace clic en él: */
  a {
    color: blue;
  }
  
  a:link {
    background-color: red;
  }
  
  a:active {
    background-color: green;
  }

  /* Color de fondo de lista */
  ul {
    list-style-type: none;
    background-color: white;
  }
  
  li:nth-of-type(1):hover {
    background-color: red;
  }
  
  li:nth-of-type(2):hover {
    background-color: green;
  }
  
  li:nth-of-type(3):hover {
    background-color: blue;
  }

  /* SeudoElementos */
  /* Establece la primera línea de todos los párrafos (p) en negrita y roja: */
  p::first-line {
    font-weight: bold;
    color: red;
  }

  /* La primera letra estará en negrita, en color crimson y un tamaño de 60 píxeles */
  p::first-letter {
    font-weight: bold;
    color: crimson;
    font-size: 60px;
}

/* Añadir una flecha al final de un párrafo: */
p {
    font-size: 16px;
    line-height: 2;
  }
  
  p::after {
    content: "→";
    font-size: 20px;
    position: absolute;
    bottom: 0;
    right: 0;
  }

  /* Cambiar el color de fondo del texto seleccionado: */
  body {
    color: black;
    background-color: white;
  }
  
  ::selection {
    background-color: red;
  }

  /* Añadir contenido antes y después del elemento. */
  h1::before {
    content: url("https://icons.iconarchive.com/icons/gartoon-team/gartoon-action/48/dialog-apply-icon.png");
}
```




