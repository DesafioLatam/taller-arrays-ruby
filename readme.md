# Taller Arrays en Ruby

[https://github.com/DesafioLatam/taller-estructuras-control](https://github.com/DesafioLatam/taller-estructuras-control)

*INSTRUCCIONES*:

- Realiza los ejercicios utilizando tu editor de texto Atom o Sublime.

- Guarda los cambios y súbelos a un repositorio en tu cuenta de Github.

- Una vez enviados los últimos cambios, sube el link de tu repositorio de Github en el desafío de la sección correspondiente en la plataforma.



## Arrays

### Ejercicio 1
Dado el array:

~~~ruby
arreglo = [1,2,3,9,1,4,5,2,3,6,6]
~~~

1. Imprimir el primer elemento.
2. Imprimir el último elemento.
3. Imprimir, utilizando una iteración, todos los elementos.
4. Imprimir, utilizando una iteración, todos los elementos junto con su índice.
5. Imprimir todos los elementos que se encuentren en una posición (índice) par.

### Ejercicio 2
Dado el array:

~~~ruby
a = [1,2,3,9,1,4,5,2,3,6,6]
~~~

1. Eliminar el último elemento.

2. Eliminar el primer elemento.

3. Eliminar el elemento que se encuentra en la posición media, si el arreglo tiene un número par de elementos entonces remover el que se encuentre en la mitad izquierda.

	> Ejemplo, en el arreglo [1,2,3,4] se elimina el número 2.

4. Borrar el último elemento mientras ese número sea distinto a 1.
5. Utilizando un arreglo vacío auxiliar y operaciones de push and pop invertir el orden de los elementos en un arreglo.


### Ejercicio 3
Dado el array:

~~~ruby
a = [1,2,3,9,1,4,5,2,3,6,6]
~~~

1. Eliminar todos los números pares del arreglo.
2. Obtener la suma de todos los elementos del arreglo utilizando *.each*
3. Obtener el promedio de los elementos del arreglo.
4. Incrementar todos los elementos en 1 retornando un nuevo arreglo.

### Ejercicio 4
Se tiene un arreglo de productos:

~~~rb
products = %w(Producto1 Producto2 Producto3 Producto4)

html = ''
products.each do |i|
  html += "<div class='product'></div>\n"
end

~~~

Se pide que el output sea un string con el siguiente contenido:

~~~html
<div class='product'><p> Producto1 </p></div>
<div class='product'><p> Producto2 </p></div>
<div class='product'><p> Producto3 </p></div>
<div class='product'><p> Producto4 </p></div>
~~~

### Ejercicio 5
Se tiene un arreglo de productos y precios:

~~~rb
products = %w(Producto1 Producto2 Producto3 Producto4)
prices = %w[1000 2000 1500 950]

html = ''
products.each do |i|
  html += "<div class='product'>"
  html += "</div>\n"
end
~~~

Se pide que el output sea:

~~~html
<div class='product'><p> Producto1 </p><p> Precio: 1000 </p></div>
<div class='product'><p> Producto2 </p><p> Precio: 2000 </p></div>
<div class='product'><p> Producto3 </p><p> Precio: 1500 </p></div>
<div class='product'><p> Producto4 </p><p> Precio: 950 </p></div>
~~~

### Ejercicio 6
Dado los arrays

~~~ruby
a = [1,2,3,9,12,31, "domingo"]
b = ["lunes", "martes", "miércoles", "jueves", "viernes", "sábado", "domingo"]
~~~
Obtener:

1. La concatenación de a y b. (hint: Los elementos que se repiten en a y b pueden aparecer dos veces en el resultado).
2. La unión de a y b. (hint: Los elementos que se repiten en a y b NO deben aparecer repetidos en el resultado).
3. La intersección de a y b. (hint: El resultado debe estar compuesto por los elementos que se repiten en a y b).
4. Intercalar los elementos:

~~~ruby
resultado = [[1, "lunes"], [2, "martes"], [3, "miércoles"], [9, "jueves"], [12, "viernes"], [31, "sábado"], ["domingo", "domingo"]]
~~~
