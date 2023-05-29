# Clase \#5 - Qué son los algoritmos y cómo construir algoritmos desde cero

1. Qué son Algoritmos?
    
    "Un algoritmos es simplemente una serie de instrucciones a seguir, para resolver un problema."

1. Cuándo se debe crear algoritmos?

    Siempre que queremos construir una secuencia de pasos para solucionar un problema.

1. Cuál es la estrategia?
  
    De manera independiente, en cualquiera de los siguientes dos casos:
    1. Cuando alguien te presenta un problema para que lo resuelvas.
    1. Cuando encuentras un problema a resolver.
___

## Método de las [<span title="Son cinco q's, porque en portugués, las palabras como 'cual' se escriben con Q">5Q's</span>](#método-de-las-5qs-para-construir-un-algoritmo) para construir un **algoritmo**:



Analiza el problema de manera crítica:
(Intenta explicar el problema para ti mismo\(a\) en **voz alta**, luego pide más información y/o investiga hasta que comprendas el problema en su totalidad.)

1. **[<span title="Quais">Cuáles</span>](#método-de-las-5qs-para-construir-un-algoritmo) son los datos de entrada necesários?**
1. **[<span title="O qué">Qué</span>](#método-de-las-5qs-para-construir-un-algoritmo) debo hacer con estos datos?**
1. **[<span title="Quais">Cuáles</span>](#método-de-las-5qs-para-construir-un-algoritmo) son las restricciones de este problema?**
1. **[<span title="Qual">Cuál</span>](#método-de-las-5qs-para-construir-un-algoritmo) es el resultado esperado?**
1. **[<span title="Qual">Cuál</span>](#método-de-las-5qs-para-construir-un-algoritmo) es la secuencia de pasos a seguir para llegar al resultado esperado?**

___

## Vamos a aplicar este método!
Comencemos resolviendo tres problemas para practicar nuestro método:
  1. [Llamar a un amigo](#problema-1---llamar-a-una-amigoa)
  1. [Pago por hora de un empleado](#problema-2---pago-por-hora-de-un-empleado)
  1. [Adivina el número](#problema-3---adivina-el-número)

### Problema 1 - Llamar a un\(a\) amigo\(a\)
Construye un **algoritmo** para llamar a un amigo.
1. Cuáles son los datos de entrada necesarios?
    * Un teléfono (celular).
    * El número de la persona a llamar.
1. Qué debo hacer con estos datos?
    * Debo usar el celular para llamar a mi amigo.
1. Cuáles son las restricciones de este problema?
    * Si mi amigo no me contesta, dejar un mensaje diciendo: "Devuélveme la llamada".
1. Cuál es el resultado esperado?
    * Lograr hablar con mi amigo(a).
1. Cuál es la secuencia de pasos a seguir para llegar al resultado esperado?
    1. Coger el teléfono.
    1. Si está bloqueado con contraseña, desbloquear primero.
    1. Verificar si hay señal.
    1. Digita el número de tu amigo(a).
    1. Oprime el botón para llamar.
    1. Espera a que conteste el wey.
    1. Si contesta, conversa con fe.
    1. Si no contesta, dejar un mensaje diciendo: "Devuélveme la llamada".

### Problema 2 - Pago por hora de un empleado
Escribir un programa que devuelva el precio por hora de un de un trabajador sobre la base de su sueldo mensual y las horas trabajadas por mes.
1. Cuáles son los datos de entrada necesarios?
    * El salario mensual.
    * Horas trabajadas por mes.
1. Qué debo hacer con estos datos?
    * Debo usarlos para calcular el precio por hora que un empleado recibe, usando la fórmula: **salario mensual / horas trabajadas**.
1. Cuáles son las restricciones de este problema?
    * Los valores deben ser entregados solo en formato pago por hora.
1. Cuál es el resultado esperado?
    * El pago por hora que gana un empleado.
1. Cuál es la secuencia de pasos a seguir para llegar al resultado esperado?
    1. Pedir los datos necesarios:
        * Preguntar cuánto gana por mes.
        * Guardar esa información.
        * Preguntar cuántas horas trabaja por mes.
        * Guardar esa información.
    1. Calcular el pago por hora de la persona (salario mensual / horas trabajadas).
    1. Mostrar el pago por hora de la persona.

### Problema 3 - Adivina el número
Escriba un programa que, al inicio, genera un número aleatorio del 1 al 10 y permite que el usuario introduzca un número hasta que el valor generado al inicio del programa sea adivinado correctamente.

El programa debe indicar si el número introducido por el usuario fue mayor o menor que el número aleatorio generado.
1. Cuáles son los datos de entrada necesarios?
    * El valor aleatorio del 1 al 10.
    * Un número proporcionado por el usuario.
1. Qué debo hacer con estos datos?
    1. Debo tomar el valor que fue generado aleatoriamente y compararlo con el valor introducido por el usuario.
    1. Si el valor introducido por el usuario fuere mayor o menor que que el valor aleatorio generado, informar al usuario y pedir al usuario que introduzca otro número, hasta que el número aleatorio sea adivinado.
1. Cuáles son las restricciones del problema?
    * El programa no debe terminar hasta el número aleatorio sea adivinado correctamente.
    * El usuario debe ser capaz de jugar cuantas veces quiera.
1. Cuál es el resultado esperado?
    * El programa debe verificar que el valor introducido por el usuario es igual al valor generado aleatoriamente.
1. Cuál es la secuencia de pasos a seguir para llegar al resultado esperado?
    1. Generar un valor aleatorio del 1 al 10.
    1. Almacenar o guardar ese valor.
    1. Recibir el valor introducido por el usuario.
    1. Comparar el valor del usuario con el valor aleatorio.
    1. Si el valor del usuario fuera mayor que el valor aleatorio, mostrar "El valor es demasiado alto", y volver al paso 3.
    1. Si el valor del usuario fuera menor que el valor aleatorio, mostrar "El valor es demasiado bajo", y volver al paso 3.
    1. Si el valor del usuario fuera igual al valor aleatorio, Mostrar "Acertaste!" Y preguntar al usuario si quiere volver a jugar.
    1. Si el jugador acepta jugar otra vez, volver al paso 1.

[**Volver al Inicio**](/)
