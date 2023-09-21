<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 

# Actividad

Completa el siguiente código HTML añadiendo el contenido multimedia correspondiente en cada sección:

- 4 Imagenes
- 2 Videos
- 4 Audios
- 2 Inline Frame
- Utiliza encabezados para títulos en cada elemento 

Crea una descripción para cada elemento utilizando párrafos

Además, puedes emplear etiquetas.


## Plantilla Inicial

```html
<!DOCTYPE html>
<html>

<head>
    <title>Etiquetas Multimedia HTML5</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #333333;
            color: white;
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: blue;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>

    <header>
        <h1>Etiquetas Multimedia HTML5</h1>
        <h3>La forma más fácil de agregar multimedia a tus sitios web</h3>
    </header>

    <section>
        <h2>Imágenes</h2>
        <p>Contenido sobre imágenes...</p>
    </section>

    <section>
        <h2>Videos</h2>
        <p>Contenido sobre videos...</p>
    </section>

    <section>
        <h2>Audios</h2>
        <p>Contenido sobre audios...</p>

    </section>

    <section>
        <h2>iFrames</h2>
        <p>Contenido sobre iframes...</p>
    </section>

    <footer>
        Nombre Completo
        <br>
        <br>
        CESDE
        <br>
        <br>
        &copy;2023
    </footer>

</body>

</html>
```

## Solucion

Este es el codigo empleado para hacer la etiqueta multimedia

Link para descargar el archivo completo

https://drive.google.com/file/d/11I2bTH-PMAmkexQ-skTGSfs1HH_jYAGr/view?usp=drive_link

``` html
<!DOCTYPE html>
<html>

<head>
    <title>Sonidos Marinos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #000000;
            color: white;
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: blue;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>

    <header>
        <h1>Sonidos marinos no identificados</h1>
        <h3>Durante investigaciones cientificas en las profundidades del mar, se han manifestado sucesos muy misteriosos <br>Aqui estaran una parte de ellos, con imagenes <strong>(de referencia)</strong> y audios de los sonidos mas aterradores captados en lo mas profundo del oceano </h3>
    </header>

    <section>
        <h2>Imagenes</h2>
        <h3>Upsweep</h3>
        <p>(traducido literalmente como «barrido arriba») es un sonido no identificado detectado por el sistema de hidrófonos autónomos de la <strong>Administración Nacional Oceánica y Atmosférica</strong>. Este sonido estaba presente cuando el Laboratorio Ambiental Marino del Pacífico comenzó a grabar en agosto de 1991, y tiene una larga serie de sonidos de barrido de varios segundos de duración cada uno. La fuente fue lo suficientemente alta como para ser registrada en todo el Pacífico.</p>
        <img src="Upsweep_Espectrograma.jpg" width="350">

        <h3>Bloop</h3>
            <p>es el nombre dado a un sonido muy potente y de frecuencia ultra-baja detectado por la Administración Nacional Oceánica y Atmosférica en 1997. El sonido es compatible con los ruidos generados por criosismos en grandes icebergs, o grandes icebergs raspando el fondo del océano; no obstante, eso no explica la fuerza del sonido y el alcance de este, haciendo que esto solo sea una hipótesis.</p>

            <img src="BloopImagen.jpg" width="350">
        
        <h3>Julia</h3>
            <p>Julia es un sonido grabado el 1 de marzo de 1999 por la Administración Nacional Oceánica y Atmosférica de Estados Unidos. Según la organización, la fuente del sonido parecía provenir de <strong>alguna criatura colosal por su parecido a un rugido.</strong> Era lo suficientemente fuerte como para ser detectado por todo el sistema de hidrófonos autónomos del Pacífico. El sonido no identificado duró aproximadamente 15 segundos. Debido a la dificultad en la triangulación, el punto de origen podría ser entre el Estrecho de Bransfield y el Estrecho del Cabo Adare.</p>   
            <img src="Julia.jpg" width="350"> 
        
        <h3>Slow Down</h3>
            <p>Slow Down es un sonido grabado el 19 de mayo de 1997, en el Océano Pacífico Ecuatorial por la Administración Nacional Oceánica y Atmosférica. Según la NOAA, la fuente del sonido es más probable que fuera un gran iceberg en contacto con el fondo marino <br> El sonido recibió ese nombre porque la frecuencia del sonido disminuye lentamente durante aproximadamente 7 minutos. Fue grabado por un hidrófono autónomo. El sonido ha sido detectado varias veces al año desde 1997.
            </p>

            <img src="SlowDown.jpg" width="350">
    </section>

    <section>
        <h2>Videos</h2>
        <video src="BajoAguaVideo.mp4" controls width="690"></video>

        <p>Pensemos un rato juntos e imaginemos con estos videos, antes de escuchar los audios, como te sentirias tu... Nadar tranquilamente a la deriva, sentir que te alejas poco a poco de la zona segura, intentas sumergir la cabeza y de repente <strong><span style="color: rgb(255, 0, 0);">escuchar un fuerte y desconocido sonido, que se va desvaneciendo a medida que pasa el tiempo.</span></strong></p>

        <video src="OlasVideo.mp4" controls width="690"></video>


    </section>

    <section>
        <h2>Audios</h2>
        <h3>Sonido de Upsweep</h3>
        <p>Este es el sonido recogido de Upsweep en las profundidades</p>
        <audio src="UpsweepSonido.ogg" controls></audio>

        <h3>Sonido de Bloop</h3>
        <p>Este es el sonido recogido de Bloop en las profundidades</p>
        <audio src="BloopSonido.ogg" controls></audio>

        <h3>Sonido de Julia</h3>
        <p>Este es el sonido recogido de Julia en las profundidades</p>
        <audio src="JuliaSonido.ogg" controls></audio>

        <h3>Sonido de SlowDown</h3>
        <p>Este es el sonido de Slow Down en las profundidades</p>
        <audio src="SlowdownSonido.ogg" controls></audio>

    </section>

    <section>
        <h2>iFrames</h2>
        <h3>Videos documentales</h3>
        <p>Luego de este recorrido, te dejare algunos videos muy interesantes sobre las profundidades del oceano, lo que no conocemos y lo que falta por descubrir</p>

        <a href="https://www.youtube.com/watch?v=wBMDx9hVpEM" target="_blank">Video de las profunidades del oceano</a> <br> 
        <a href="https://www.youtube.com/watch?v=hWh_hVdZbxA" target="target">Video de el iceberg del oceano</a>

    </section>

    <footer>
        Miguel Angel Roldan Cardona 
        <br>
        <br>
        CESDE
        <br>
        <br>
        &copy;2023
    </footer>

</body>

</html>
```








