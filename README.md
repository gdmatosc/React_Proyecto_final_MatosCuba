# Proyecto compuwork 馃捇
Proyecto final del curso de React de Coderhouse.

Se ha agregado 3 archivos .gif que muestran las principales funcionalidades de la aplicaci贸n que ha sido desplegada en Netlify

## 1. Descripci贸n de dise帽o de negocio 馃捈
El proyecto consiste en una tienda de productos tencol贸gicos para computadoras denominado Compuwork.
Se tienen actualmente 6 productos clasificados en 3 categor铆as:
1. Perif茅ricos: dispositivos que se conectan directamente a la PC o laptop
2. Comunicaciones: dispositivos para comunicaciones de red por cable o wifi
3. El茅ctricos: dispositivos que permiten conexiones electricas, luz as铆 como la estabilizaci贸n de la corriente el茅trica

## 2. Flujo de compras 馃攦
1. Al inicio se muestran directamente todos los productos
2. Se da click en el bot贸n de "ver m谩s" para ir a la pantalla de detalle del producto
3. Se puede aumentar o disminuir la cantidad de productos y se agrega al carrito con el bot贸n agregar
4. Se puede acceder al carrito de compras por el bot贸n que aparece en la parte inferior del card de la p谩gina de detalles de cada producto o mediante el 铆cono de carrito de compras
5. Para realizar la orden de compra se debe llenar los datos de compras que se encuentra debajo del resumen de producto del carrito
6. Luego se da click en el bot贸n generar compra y aparecer谩 un mensaje que le mostrar谩 su c贸digo de compra

Opcionalmente
- Si el usuario lo desea puede dar click en el bot贸n registro en cualquier momento para que su nombre de usuario de la web pase de an贸nimo a su nombre, considerar que este registro no tiene relaci贸n con los datos de compra.

## 3.Limitaciones t茅cnicas 鉂?
1. No se ha implementado el control de stock, solo se encuentra como atributo de bd para cada producto con un valor de 5 
2. No se ha implementado la eliminaci贸n por producto, solo se muestra el 铆cono X
3. Se ha implementado el resumen de orden compra por b煤squeda del id, ahora esa p谩gina tiene la ruta /miorden
4. Se ha implementado la l贸gico de verificaci贸n del email ingresado 2 veces, aparece un mensaje de advertencia si no coinciden los dos emails cuando se termina de ingresar el segundo email
~~3. No se ha implementado el resumen de la creaci贸n de orden de compra, solo se ha generado la p谩gina thank-you conteniendo el id del orden en la url con el mensaje gracias por su compra~~
~~4. No se ha implementado la l贸gica de repetir el email 2 veces, solo se ha desarrollado el control de ingreso de d铆gitos en todos los input~~
5. Netlify est谩 mostrando su propio mensaje de page not found para rutas inexistentes, a pesar que la configuraci贸n local funciona con PageNotFound.jsx
6. Netlify est谩 mostrando el mensaje de Page not found al digitar directamente una url v谩lida o al actualizar una ruta v谩lida

## 4.Librerias usadas 馃敀馃敡
Se ha usado:
1. tailwind: reduce la cantidad de archivos de css y facilita su uso
2. vite: optimiza la ejecuci贸n de React y reduce sus vulnerabilidades
3. sweetalert
4. react-router