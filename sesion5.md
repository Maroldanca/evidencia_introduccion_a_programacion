<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 5 


# Actividad: Diseñar un formulario de pedido de un producto

## Objetivo:

Aplicar los conocimientos sobre los tipos de etiquetas HTML para diseñar un formulario de pedido de un producto.

## Instrucciones:

+ Crear un nuevo documento HTML.
+ Crear un formulario con los siguientes campos:
+ Nombre del producto
+ Cantidad
+ Precio unitario
+ Precio total
+ Dirección de envío
+ Información de contacto (nombre, correo electrónico, número de teléfono)

Agregar los siguientes campos relacionados al formulario:

- Método de pago
- Fecha de entrega
- Comentarios

Utilizar las etiquetas HTML apropiados para cada campo.

## Solucion

Este es el codigo utilizado para crear el formulario en html

``` html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario</title>
</head>

<body>

    <form action="" method="post" enctype="application/x-www-form-urlencoded">

        <h1>PRODUCTOS</h1>
        <h2>¡Pide tu producto aqui!</h2>

        <div>
            <label for="idproductos">¿Que quieres pedir?</label>
            <select name="productos" id="idproductos">
                <option value="Lapiceros">Lapiceros</option>
                <option value="Borradores">Borradores</option>
                <option value="Libros">Libros</option>
                <option value="Estanterias">Estanterias</option>
                <option value="Computadores">Computadores</option>
                <option value="Sillas">Sillas</option>
                <option value="Mesas">Mesas</option>
            </select>
        </div>

        <br>

        <div>
            <label for="idcantidad">¿Cuantos quieres?</label>
            <input type="number" id="idcantidad">
        </div>

        <br>

        <div>
            <label for="idprecio">Precio unitario</label>
            <input type="text" id="idprecio">
        </div>

        <br>

        <div>
            <label for="idtotal">Precio total</label>
            <input type="text" id="idtotal">
        </div>

        <br>

        <div>
            <label for="iddireccion">*Direccion</label>
            <input type="text" id="iddireccion">
        </div>

        <h1>¡Tu informacion!</h1>
        <div>
            <label for="idnombre">*Nombre</label>
            <input type="text" name="nombre" id="nombre">
        </div>

        <br>

        <div>
            <label for="idapellido">*Apellido</label>
            <input type="text" name="apellido" id="idapellido">
        </div>

        <br>

        <div>
            <label for="idcorreo">*Correo Electronico</label>
            <input type="email" name="correo" id="idcorreo">
        </div>

        <br>

        <div>
            <label for="idnumero">*Telefono</label>
            <input type="tel" name="telefono" id="idnumero">
        </div>

        <h1>¡Añade tu metodo de pago!</h1>
        <div>
            <label for="idmetodopago">Metodo de pago</label>
            <input type="text" placeholder="Otros..." name="pago" id="idmetodopago">
            <select name="metodos" id="idmetodopago">
                <option value="Tarjeta">Tarjeta de credito</option>
                <option value="Efectivo">Efectivo</option>
                <option value="Transferencia">Transferencia</option>
            </select>
        </div>

        <br>

        <div>
            <label for="idfecha">Fecha de entrega</label>
            <input type="date" name="fecha" id="idfecha">
        </div>

        <br>

        <div>
            <h2>Comentarios</h2> 
            
            <label for="idcomentarios">Comenta aqui</label>
            <textarea name="comentarios" id="idcomentarios" placeholder="¿Que sugerencias tienes?" rows="10" cols="50"></textarea>
            
            <br>
            <br>
            <br>
            <br>

            <button type="submit" name="comentarios" id="idcomentarios" value="Enviar">Enviar</button>
        </div>
        
    </form>

</body>

</html>

```





