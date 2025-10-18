BOOTCAMP: Data Analytics
Modulo 1 | Python básico | Evaluación final
ALUMNA: María del Rocío Sánchez Gálvez
PROMOCION: 59


EJERCICIO 3. buscar_producto(nombre): Busca un producto en el inventario por nombre y muestra sus detalles si se encuentra. 
Debe recibir el nombre del producto como parámetro.

1º establezco la funcion con def, el nombre que le quiero dar y entre parentesis la palabra clave que sera la que luego meta para que me traiga el resultado.

2º hago un bucle for para que recorra la lista, un if para que identifique si la clave que busco (el nombre del producto) está en la lista de diccionarios,producto se refiere a cada diccionario dentro de la lista pongo ["nombre"] para que dentro de cada diccionario busque por la clave llamada "nombre" y compare si su valor coincide con la fruta (nombre_producto) que le indicaré cuando ejecute la funcion. == nombre_producto: lo pongo para que compare si la palabra clave (nuevo_producto) que quiero que busque es igual a alguna clave que haya dentro de algún diccionario. hago un print para que me devuelva el producto con sus detalles si está en la lista, es decir, si se cumple la condicion. Uso la f para concatenar el texto que quiera poner con " al inicio y al final de la frase, despues de cada clave del detalle ("nombre:") seguida de lo que quiero que me traiga del diccionario. Un break para que deje de buscar cuando la encuentre. Termino con un else para que me devuelva una frase que indique que el producto no está en la lista, así yo compruebo y aseguro que está ok. Compruebo identaciones.