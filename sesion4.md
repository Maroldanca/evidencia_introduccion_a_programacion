<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 4

# Actividad: Crear una tabla HTML con información sobre productos.

Escribir una tabla HTML con 10 filas que muestre información sobre productos reales. La tabla debe tener las siguientes columnas:

- Código
- Nombre
- Descripción
- Precio
- Stock
- Fecha de creación

Además, combinar celdas en la tabla con los atributos rowspan y colspan, como se muestra en la siguiente imagen.

## Solucion

Este es el codigo utilizado para crear la tabla con todas sus columnas y filas respectivamente.

``` html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pruebas</title>
</head>

<body>
    <table border="1" cellpadding="5" cellspacing="10">
        <thead>
            <tr>
                <th>Codigo</th>
                <th>Nombre</th>
                <th>Descripcion</th>
                <th>Precio</th>
                <th>Stock</th>
                <th>Fecha de creacion</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td rowspan="2">001</td>
                <td rowspan="2">iPhone</td>
                <td>Pantalla	3,5 pulgadas
                    Resolución	320x480 pixeles
                    Batería	Li-Ion battery
                    Memoria RAM	128 MB
                    Memoria interna	 4/8/16 GB
                    Procesador	ARM 1156
                    Sistema operativo	iOS 1.0
                    Cámara principal	2MP
                    Cámara frontal	No tenía</td>
                <td rowspan="2">2.023.983 COP</td>
                <td rowspan="2">4</td>
                <td rowspan="2">29-06-2007</td>
            </tr>

            <tr>
                <td>Marcó un punto de inflexión en la industria de los teléfonos móviles al combinar un teléfono, un reproductor de música y un dispositivo de comunicación en un solo dispositivo elegante y funcional</td>
            </tr>

            <tr>
                <td rowspan="2">002</td>
                <td rowspan="2">iPhone 3</td>
                <td>Pantalla	3,5 pulgadas
                    Resolución	320x480 píxeles
                    Batería	 Li-Ion battery
                    Memoria RAM	128 MB
                    Memoria interna	 8/16 GB
                    Procesador	412 MHz ARM 11
                    Sistema operativo	iOS 1.0
                    Cámara principal	2MP
                    Cámara frontal	No tenía</td>
                <td rowspan="2">1.212.767 COP</td>
                <td rowspan="2">5</td>
                <td rowspan="2">11-07-2008</td>
            </tr>

            <tr>
                <td> fue un smartphone innovador en su época y representó una mejora significativa con respecto al primer iPhone. </td>
            </tr>

            <tr>
                <td rowspan="2">003</td>
                <td rowspan="2">iPhone 3S</td>
                <td>
                    Pantalla	3,5 pulgadas
                    Resolución	320x480 pixeles
                    Batería	Li-Ion battery
                    Memoria RAM	256 MB
                    Memoria interna	8/16/32 GB
                    Procesador	600 MHz Cortex-A8
                    Sistema operativo	iOS 3.0
                    Cámara principal	3 MP
                    Cámara frontal	No tenía</td>
                <td rowspan="2">1.212.767 COP</td>
                <td rowspan="2">6</td>
                <td rowspan="2">4-06-2009</td>
            </tr>

            <tr>
                <td> el iPhone 3GS fue un paso importante en la evolución de la línea de iPhones de Apple, ya que mejoró significativamente el rendimiento, la cámara y la capacidad de procesamiento en comparación con sus predecesores</td>
            </tr>

            <tr>
                <td rowspan="2">004</td>
                <td rowspan="2">iPhone 4</td>
                <td>Pantalla	3,5 pulgadas
                    Resolución	640x960 píxeles
                    Batería	1.420 mAh
                    Memoria RAM	512 MB
                    Memoria interna	8/16/32 GB
                    Procesador	A4
                    Sistema operativo	iOS 3.0
                    Cámara principal	5 MP
                    Cámara frontal	VGA</td>
                <td rowspan="2">2.632.395 COP</td>
                <td rowspan="2">7</td>
                <td rowspan="2">6-06-2010</td>
            </tr>

            <tr>
                <td>El iPhone 4 se considera uno de los dispositivos más influyentes en la historia de los smartphones debido a su diseño vanguardista, su pantalla Retina, y las características de hardware y software avanzadas que introdujo</td>
            </tr>

            <tr>
                <td rowspan="2">005</td>
                <td rowspan="2">iPhone 5</td>
                <td>Pantalla	4,0 pulgadas
                    Resolución	640x1136 píxeles
                    Batería	1.440 mAh
                    Memoria RAM	1 GB
                    Memoria interna	8/16/32/64 GB
                    Procesador	A6
                    Sistema operativo	iOS 4.0
                    Cámara principal	8 MP
                    Cámara frontal	1,2 MP</td>
                <td rowspan="2">1.618.375 COP</td>
                <td rowspan="2">4</td>
                <td rowspan="2">4-09-2012</td>
            </tr>

            <tr>
                <td>El iPhone 5 fue bien recibido por su diseño, rendimiento y conectividad avanzada. Continuó el legado de innovación de Apple en el mercado de los smartphones y fue una elección popular entre los usuarios de iPhone en su época.</td>
            </tr>

            <tr>
                <td rowspan="2">006</td>
                <td rowspan="2">iPhone 6</td>
                <td>
                    Pantalla	4,7 pulgadas
                    Resolución	750x1334 píxeles
                    Batería	1.810 mAh
                    Memoria RAM	1 GB
                    Memoria interna	8/16/32/64/128 GB
                    Procesador	A8
                    Sistema operativo	iOS 8.0
                    Cámara principal	8 MP
                    Cámara frontal	1,2 MP</td>
                <td rowspan="2">1.825.236 COP</td>
                <td rowspan="2">8</td>
                <td rowspan="2">10-09-2014</td>
            </tr>

            <tr>
                <td>El iPhone 6 fue un dispositivo popular y exitoso debido a su diseño elegante, pantalla más grande y un rendimiento mejorado. Además, introdujo características como Apple Pay y Touch ID que aumentaron la comodidad y la seguridad del usuario</td>
            </tr>

            <tr>
                <td rowspan="2">007</td>
                <td rowspan="2">iPhone 7</td>
                <td>Pantalla	4,7 pulgadas
                    Resolución	640x1136 píxeles
                    Batería	1.960 mAh
                    Memoria RAM	2 GB
                    Memoria interna	32/128/256 GB
                    Procesador	A10
                    Sistema operativo	iOS 10.0.1
                    Cámara principal	12 MP
                    Cámara frontal	7 MP</td>
                <td rowspan="2">3.443.611 COP</td>
                <td rowspan="2">4</td>
                <td rowspan="2">4-09-2016</td>
            </tr>

            <tr>
                <td>El iPhone 7 fue un dispositivo popular y representó una mejora significativa en términos de rendimiento, cámara y resistencia al agua en comparación con su predecesor.</td>
            </tr>

            <tr>
                <td rowspan="2">008</td>
                <td rowspan="2">iPhone 8</td>
                <td>
                    Pantalla	5,5 pulgadas
                    Resolución	1080x1920 píxeles
                    Batería	2.691 mAh
                    Memoria RAM	3 GB
                    Memoria interna	64/256 GB
                    Procesador	A11
                    Sistema operativo	iOS 11
                    Cámara principal 	12 MP 
                    Cámara frontal	7 MP</td>
                <td rowspan="2">3.569.350 COP</td>
                <td rowspan="2">10</td>
                <td rowspan="2">2-09-2017</td>
            </tr>

            <tr>
                <td>El iPhone 8 fue una actualización sólida en la línea de iPhones de Apple, con mejoras en rendimiento, cámara y carga inalámbrica. </td>
            </tr>

            <tr>
                <td rowspan="2">009</td>
                <td rowspan="2">iPhone X</td>
                <td>
                    Pantalla	5,8 pulgadas
                    Resolución	1125x2436 píxeles
                    Batería	2.716 mAh
                    Memoria RAM	3 GB
                    Memoria interna	64/256 GB
                    Procesador	A11
                    Sistema operativo	iOS 11.1.1
                    Cámara principal (doble)	12 MP + 12 MP
                    Cámara frontal	7 MP</td>
                <td rowspan="2">4.660.435 COP</td>
                <td rowspan="2">8</td>
                <td rowspan="2">15-11-2017</td>
            </tr>

            <tr>
                <td>El iPhone X representó un cambio importante en el diseño y la funcionalidad de los iPhones de Apple. Su pantalla sin bordes, Face ID y cámaras avanzadas lo convirtieron en un dispositivo altamente innovador y deseado en su momento. Su diseño y tecnología avanzada lo hicieron destacar en el mercado de los smartphones</td>
            </tr>

            <tr>
                <td rowspan="2">010</td>
                <td rowspan="2">iPhone 11 Pro Max</td>
                <td>
                    Pantalla	
                    6,5 pulgadas
                    
                    Resolución	1242x2688 píxeles
                    Batería	3.500 mAh 
                    Memoria RAM	6 GB
                    Memoria interna	64/256/512 GB
                    Procesador	A13 Bionic
                    Sistema operativo	iOS 13
                    Cámara principal (triple) 	12 MP +12 MP + 12 MP
                    Cámara frontal	12 MP</td>
                <td rowspan="2">5.877.259 COP</td>
                <td rowspan="2">9</td>
                <td rowspan="2">11-09-2019</td>
            </tr>

            <tr>
                <td>En resumen, el iPhone 11 Pro Max fue un dispositivo emblemático que combinó un diseño premium, un rendimiento potente y un conjunto de cámaras avanzadas para brindar una experiencia de usuario excepcional.</td>
            </tr>
        </tbody>
    </table>
</body>

</html>

```



