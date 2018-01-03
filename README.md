# GRID SYSTEM

Es una estructura de dos dimensiones que consta de líneas verticales y horizontales que nos ayuda a posicionar de manera organizada los elementos de un documento. En Responsive Web Design, las grids nos ayudan a proporcionar una experiencia uniforme en múltiples dispositivos aunque cuenten con diferentes tamaños de pantalla.


## ELEMENTOS DEL GRID SYSTEM

### Container

El objetivo del container es establecer el ancho de toda la grid. El ancho del container generalmente es del 100%, pero también es posible que se desee establecer un ancho máximo para pantallas más grandes.

### Row

El propósito del row es evitar que las columns dentro de él se desborden en otras rows.

### Columns

El proposito de las columns es contener a los elementos que queremos mostrar en nuestro sitio web.

### Gutters

Los gutters son los espacios entre las columns.



La unidad de medida de las cajas de nuestro grid será columnas. Dado de que nuestro grid consiste de 12 columnas, nuestras cajas pueden medir “1 columna”, “2 columnas”, “3 columnas” y así sucesivamente hasta llegar a “12 columnas”.

Si nuestra caja mide “6 columnas”, nuestra fórmula será el número de columnas entre 12 por 100, es decir: 

### (6/12) * 100 

el resultado de esta operación es 50, por lo que nuestras cajas de “6 columnas” medirán 50% del ancho total.


Visualmente esto se representa de la siguiente manera,


Nuestros cajas ahora medirán 50% cada uno, y así sumarán un 100%, que en columnas serán 6 + 6 para que sumados sean 12.

Entonces hagamos la matemática para tener los valores de las columnas del 1 al 12:

* 12 columnas = 100%
* 11 columnas = 91.66666666666666%
* 10 columnas = 83.33333333333334%
* 9 columnas  = 75%
* 8 columnas  = 66.66666666666666%
* 7 columnas  = 58.333333333333336%
* 6 columnas  = 50%
* 5 columnas  = 41.66666666666667%
* 4 columnas  = 33.33333333333333%
* 3 columnas  = 25%
* 2 columnas  = 16.666666666666664%
* 1 columna   = 8.333333333333332%


Con estos valores podemos empezar a armar el grid, siempre teniendo en cuenta de que la suma del ancho de nuestras cajas (colocadas de forma horizontal) ocupen el 100% del espacio.


