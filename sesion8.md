<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 

## Actividad: Aplicando estilos con selectores CSS

El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.

Pasos:

Crea el esqueleto de una página web simple con la siguiente estructura:

- Encabezado <header>
- Tres párrafos <p>
- Una imagen <img>
- Un pie de página <footer>
- Aplica los siguientes estilos usando selectores de etiqueta:

- Color rojo a los encabezados <h1>
- Color azul a los párrafos <p>
- Borde grueso negro a la imagen <img>
- Aplica los siguientes estilos usando seleccionadores de clase:

- Color verde a los elementos con la clase ".destacado"
- Tamaño de fuente grande a los elementos con la clase ".grande"
- Aplica los siguientes estilos usando seleccionadores de ID:

- Color amarillo al elemento con ID "#principal"
- Sombra al elemento con ID "#sombras"
- Aplica los siguientes estilos usando seleccionadores descendientes:

- Color gris a los párrafos dentro de un <div>
- Centrar el contenido de la sección <section>

## Solucion


Link para descargar: https://drive.google.com/drive/u/0/folders/16yESBqmeppkLkeH67YVIMJlvxCNUVprm

### Codigo en html (con codigo interno y inline)
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pagina CSS</title>

    <link rel="stylesheet" type="text/css" href="index.css">

    <style>
        h1 {
            color: red;
        }

        p {
            color: blue;
        }

        p+div {
            color: rgb(110, 108, 108);
        }

        section {
            text-align: center;
        }

        .bordeado {
            border: 7px solid #000;
            width: 275px;
            height: 183px;

        }


        .bordes {
            margin: 0;
            padding: 0;
        }

        
    </style>

</head>

<body class="bordes">
    <header class="degradado">
        <section>
            <div class="grande">
                <h1 style="margin: 0;">Utilizacion de CSS en HTML</h1>
            </div>
            <div class="grande2">
                <h1>
                    ¿Que es CSS?
                </h1>
            </div>
        </section>
        <div>
            <p>
                <strong id="sombras">CSS (Cascading Style Sheets)</strong>
            <div>
                <p id="principal">es un lenguaje de diseño utilizado para controlar la
                    presentación y el estilo de un documento HTML o XML.<br>
                    Su función principal es separar la estructura y el contenido de un documento web de su apariencia
                    visual
                </p>
            </div>

            <div class="bordeado">
                <img src="descarga.jpg" alt="CSS contenido">
            </div>

            </p>

            <p>
                <strong id="sombras">Selección de elementos:</strong>
            <div>CSS permite seleccionar elementos HTML específicos y aplicar
                estilos a ellos.<br>
                Puedes seleccionar elementos por etiquetas, clases, identificadores u otros atributos.
            </div>
            </p>

            <p>
                <strong id="sombras">Propiedades y valores:</strong>
            <div>
                CSS define propiedades de estilo, como el color, el tamaño de
                fuente, el margen y el espaciado entre líneas, entre muchas otras.<br>
                Cada propiedad tiene un valor asociado que determina cómo se aplica el estilo.
            </div>
            </p>

            <p>
                <strong id="sombras">Estilo en cascada:</strong>
            <div>La "C" en CSS significa "cascading" (cascada). Esto significa que los
                estilos pueden aplicarse en capas y<br>
                las reglas pueden combinarse y heredarse de manera que los estilos se apliquen de manera consistente y
                predecible.</div>
            </p>
        </div>

    </header>


</body>

<div>
    <footer class="colorito">

        <p style="margin: 0;">cesde</p>
        <p>Miguel Angel Roldan Cardona</p>
        <p>Introduccion Programacion</p>

    </footer>
</div>

</html>
```
### Codigo en css

```css
.destacado {
    color: rgb(0, 255, 0);
}

.grande {
    font-size: 25px;
}

.grande2 {
    font-size: 20px;
}

#principal {
    color: yellow;
}

#sombras {
    text-shadow: 3px 7px 13px rgb(11, 32, 224);
}

.degradado {
    background: rgb(0, 250, 255);

    background: linear-gradient(0deg, rgba(0, 250, 255, 1) 59%, rgba(179, 7, 7, 1) 86%);

}

.colorito{
    background-color: aqua;
    margin-top: 10px;
    padding: 10px;

}
```


