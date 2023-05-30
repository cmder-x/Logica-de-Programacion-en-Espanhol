# Clase \#06 - 4 Conceptos Obligatorios para ser Capaz de Resolver Problemas
1. [**Variables**](#variables)
1. [**Condicionales**](#condicionales)
1. [**Ciclos de Repetición**](#ciclos-de-repetición)
1. [**Colecciones**](#colecciones)

## Variables
* Cuando alguien te dice su nombre, qué es lo que haces con ese nombre?
* Intentas guardar el nombre. Verdad?
* Dónde es que lo guardas? En tu memoria.
* Cuando alguien te envía la fecha de una cita, qué haces con esa fecha?
* La anotas en algún lugar para que puedas recordarla, o simplemente intentas guardarla en tu mente. Verdad?
* Cuando tienes que ir al mercado a hacer las compras, anotas la lista de cosas a comprar, para no olvidar esa información. No es así?

Ahora, intenta encontrar las variables del problema #02, según tu opinión:

### Pago por hora
Escribir un programa que devuelva el precio por hora de un de un trabajador sobre la base de su sueldo mensual y las horas trabajadas por mes. 

Las variables son 3:
Escribir un programa que devuelva el [**precio por hora**](#pago-por-hora) de un de un trabajador sobre la base de su [**sueldo mensual**](#pago-por-hora) y las [**horas trabajadas**](#pago-por-hora) por mes.

  * Sueldo mensual
  * Horas trabajadas
  * Pago por hora 

Hay que tener en cuenta que las variables tienen ese nombre porque el valor contenido en ellas puede cambiar a elección del programador o del usuario.

___

## Condicionales
* Cuando alguien te ofrece un volante en la calle, lo tomas sin pensar?
* Cuando encuentras una oferta sobre algo que quieres demasiado comprar, lo compras directamente sin pensarlo antes?

Espero que la respusta a ambas preguntas haya sido "no". En la vida real, tenemos la capacidad de decir si hacer algo o no, en función de ciertas condiciones, que podrían ser nuestras preferencias o las limitaciones de nuestros recursos; tendemos a priorizar o discriminar nuestas decisiones.

Bueno, en la programación ocurre lo mismo, los problemas no suelen ser tan simples como seguir instrucción a instrucción una después de la otra, sino que hay que decidir entre una actividad u otra en función de una condición o más...

Ahora analiza el problema #03, e intenta identificar los momentos en los que hay que tomar una decisió:

### Adivina el número
Escriba un programa que, al inicio, genera un número aleatorio del 1 al 10 y permite que el usuario introduzca un número hasta que el valor generado al inicio del programa sea adivinado correctamente.

El programa debe indicar si el número introducido por el usuario fue mayor o menor que el número aleatorio generado.

  Aquí tenemos algunas concionlaes en este problema:
  * Si el número introducido fue menor que el número aleatorio, informar que el número es demasiado bajo.
  * Si el número introducido fue mayor que el número aleatorio, informar que el número es demasiado alto.
  * Si el número introducido fue igual al número aleatorio, informar que el usuario acertó.

___

## Ciclos de Repetición
En el mundo real, así como en la programación, tenemos diversas situaciones donde precisamos hacer una acción varias veces, o por una determinada cantidad de veces. Por ejemplo:

* Cortar una barra de pan
* Barrer el piso
* Dar varios pasos \(caminar\) para dirigirse a algún lugar

Ahora veamos unos escenarios un poco más realistas:

### Escenario \#1
* Supongamos que para derribar un árbol, necesitamos dar 11 hachazos.
* Entonces, tendríamos que crear un comando que le ordene a una persona dar 11 hachazos a un árbol, y con eso el árbol caería.

Este fue un ejemplo de repetición que se ejecuta 11 veces para poder derribar un árbol

Es un ejemplo de repetición usada en la lógica de programación en el desarrollo de videojuegos.

### Escenario \#2
Crear un programa que recibe un número y lo incrementa en uno 10 veces.

|  |  |  |
|---|---|---|
| valor = 10
| 1º Repetición | valor = valor + 1 | valor = 11 |
| 2º Repetición | valor = valor + 1 | valor = 12 |
| 3º Repetición | valor = valor + 1 | valor = 13 |
| 4º Repetición | valor = valor + 1 | valor = 14 |
| 5º Repetición | valor = valor + 1 | valor = 15 |
| 6º Repetición | valor = valor + 1 | valor = 16 |
| 7º Repetición | valor = valor + 1 | valor = 17 |
| 8º Repetición | valor = valor + 1 | valor = 18 |
| 9º Repetición | valor = valor + 1 | valor = 19 |
| 10º Repetición | valor = valor + 1 | valor = 20 |

#### Puntos en común de los ciclos de repetición
Normalmente poseen un punto inicial  y un punto final, o también una condición de parada:

* Dejar el grifo abierto hasta que el vaso se llene.
* Nade hasta llegar al otro lado de la piscina.
* Sume todos los valores mienstras el valor sea menor que 100.
* Dé hachazos al árbol hasta que caiga.

#### Puntos clave:
* Útiles para automatizar procesos.
* Es posible definir el número de veces que se debe ejecutar un proceso.
* Poseen un punto de inicio y un punto final.
* Pueden estar sujetos a una condición.

Los ciclos también pueden ser llamados bucles, y la repetición también es conocida como iteración.

___

## Colecciones
En muchos casos, tendremos la necesidad de almacenar datos en un solo lugar, para poder trabajar con ellos, de manera conjunta o colectiva, es ahí que entran en juego la colecciones. Algunos ejemplos:

* invitados = ['Jeff', 'Amanda', 'Carol', 'Robert']
* numeros_premiados = [12, 67, 34, 100, 55]

La idea básica de una colección es la de un conjunto de datos. La más común es la Lista, pero diferentes lenguajes de programación tienen diferentes tipos de colecciones, y diferentes formas de representarlos...

### Ejemplo de uso de colecciones
Dada una colección de datos "edades" [15, 46, 75, 34, 23], imprima en pantalla la suma de esos valores:
* Definir total como 0
* Pasar por el 1º valor y sumar a total
* Pasar por el 2º valor y sumar a total
* Pasar por el 3º valor y sumar a total
* Pasar por el 4º valor y sumar a total
* Pasar por el 5º valor y sumar a total
* Mostrar el total por pantalla

Dominar estos 4 conceptos te permitirá crear algoritmos mucho más fácilmente.

[**Volver al Inicio**](/)
