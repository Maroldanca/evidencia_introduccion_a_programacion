<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 9 

### Actividad: Propiedades de espaciado y unidades de medida
Objetivo:

Practicar el uso de las propiedades de espaciado margin, padding, border y border-radius, con diferentes unidades de medida.

### Solucion

Codigo HTML
```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Propiedades de espaciado</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="contenedor">
    <div class="elemento"></div>
  </div>
</body>
</html>
```

Codigo CSS

```css
.contenedor {
  width: 200px;
  height: 200px;
}

/* Codigo de width */
.elemento {
  width: 100px;
  height: 100px;
}

/* Codigo de margin */
.elemento {
  margin: 10px;
  width: 100px;
  height: 100px;
}

/* Codigo de padding */
.elemento {
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}

/* Codigo de border */
.elemento {
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}

/* Codigo de border radius */
.elemento {
  border-radius: 10px;
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}

/* Codigo de medidas */
.elemento {
  border-radius: 10px;
  border: 5px solid red;
  margin: 50%;
  padding: 50%;
  width: 100px;
  height: 100px;
}
```
# Preguntas:

### ¿Qué es la propiedad margin?

R/= establece el margen para los cuatro lados. Es una abreviación para evitar tener que establecer cada lado por separado con las otras propiedades de margen

### ¿Qué es la propiedad padding?

R/= es la que crea el espacio o área alrededor del contenido de un elemento. Consiste en el relleno superior, derecho, inferior e izquierdo.

### ¿Qué es la propiedad border?

R/= permite definir en una única regla todos los bordes de los elementos seleccionados

### ¿Qué es la propiedad border-radius?

R/= establece el redondeo de la esquina superior izquierda del elemento. El redondeo puede ser un círculo o una elipse, o si uno de los valores es 0 , no se redondeará la esquina, dejándola cuadrada.

### ¿Qué unidades de medida se pueden utilizar para las propiedades de espaciado?

R/= Existen las siguientes:

#### Unidades absolutas

- in, pulgadas ("inches", en inglés). Una pulgada equivale a 2.54 centímetros.
- cm, centímetros.
- mm, milímetros.
- pt, puntos. Un punto equivale a 1 pulgada/72, es decir, unos 0.35 milímetros.
- pc, picas. Una pica equivale a 12 puntos, es decir, unos 4.23 milímetros.

#### Unidades relativas

- em, relativa respecto del tamaño de letra del elemento.
- ex, relativa respecto de la altura de la letra x ("equis minúscula") del tipo y tamaño de letra del elemento.
- px, (píxel) relativa respecto de la resolución de la pantalla del dispositivo en el que se visualiza la página HTML.

#### Porcentajes
El porcentaje también es una unidad de medida relativa, aunque por su importancia CSS la trata de forma separada a em, ex y px. Un porcentaje está formado por un valor numérico seguido del símbolo % y siempre está referenciado a otra medida. Cada una de las propiedades de CSS que permiten indicar como valor un porcentaje, define el valor al que hace referencia ese porcentaje.



