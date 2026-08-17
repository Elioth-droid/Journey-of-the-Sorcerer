# Capítulo_1_El hechicero aprende C#

He comenzado con mucho temor mi viaje por el sendero de los lenguajes de programación. ya había tenido mis primero pinitos en JavaScript, pero siento que esto será un asunto completamente diferente.
Para esta sección estaré usando inciialmente el **curso fundacional de C# de Microsoft** (https://www.freecodecamp.org/learn/foundational-c-sharp-with-microsoft). 
De la mano con un libro que me recomendaron, el **CsharpPlayersGuide**. una lectura que no sé si tengo la autoridad de recomendar pero que yo he encontrado muy interesante.

Este mismo libro tiene esta útil grafica de progreso para ir midiendo mi nivel de poder en C#, así que le pedí a Chat GPT que me hiciera una versión para añadir a mi repositorio.

## Registro de experiencia en C#

Cada casilla representa **25 XP**. Cuando completes una unidad de experiencia, cambia `⬜` por `✅`.

| Progreso | XP para subir | XP total al completar | Casillas de experiencia |
|:--|--:|--:|:--|
| Nivel 1 → 2 | 200 XP | 200 XP | ✅ ✅ ✅ ✅ ⬜ ⬜ ⬜ ⬜ |
| Nivel 2 → 3 | 400 XP | 600 XP | ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ |
| Nivel 3 → 4 | 600 XP | 1.200 XP | ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ |
| Nivel 4 → 5 | 800 XP | 2.000 XP | ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ |
| Nivel 5 → 6 | 1.000 XP | 3.000 XP | ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ |
| Nivel 6 → 7 | 1.200 XP | 4.200 XP | ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ |
| Nivel 7 → 8 | 1.400 XP | 5.600 XP | ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ |
| Nivel 8 → 9 | 1.600 XP | 7.200 XP | ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ |
| Nivel 9 → 10 | 1.800 XP | 9.000 XP | ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜<br>⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ |

## Regla sugerida para ganar XP por fuera de los ejercicios del libro.

- **25 XP:** terminar un ejercicio pequeño entendiendo lo que hiciste.
- **50 XP:** resolver un problema sin seguir paso a paso un tutorial.
- **100 XP:** completar una función o característica útil en un proyecto.
- **200 XP:** terminar, documentar y subir un proyecto pequeño a GitHub.

> Nota de Juan: No cuento XP por mirar un tutorial. Solo la cuento cuando escribao, pruebo y puedo explicar (a mi mismo) el código.

el Lenguaje de programación C# me permite construir muchos tipos de aplicaciones como:

- Aplicaciones de negocios
- Aplicaciones dinamicas par la Web que puedan ser usadas desde un navegador.
- Juegos, tanto 2d como 3d
- Aplicaciones científicas y financieras
- Aplicaciones basadas en la nube
- Aplicaciones Móviles.

  >Console.WriteLine("Hello World!");

  Con esto puedo logear en la consola un simple texto.

  <img width="215" height="143" alt="image" src="https://github.com/user-attachments/assets/c2fc1ba3-3496-4154-bf19-fa7092e3d9fa" />


  >[HINT!] Quizá me sienta tentado a seleccionar copiar y pegar y saltarme todo el problema de tener que escribir y poder equivocarme. Sin embargo, hay muchos beneficios en escribir el código yo mismo. Escribir el código yo mismo refuerza la memoria y el entendimiento que me ayudara a ganar una perspectiva que no tendría de otra manera. 

Pd: Cuidado con las mayúsculas en C#.

>Console.Write ("Congratulations!");
>Console.Write (" ");
>Console.Write ("You Wrote your first lines of code.");

La diferencia entre .Write y .WriteLine, es que la primera pone los logs uno después del otro, sin separaciones y .WriteLine en cambio agrega un punto y a parte e inicia una nueva línea a parte.

<img width="466" height="119" alt="image" src="https://github.com/user-attachments/assets/695b808a-a491-4355-b023-37aa2f463e39" />
<img width="305" height="134" alt="image" src="https://github.com/user-attachments/assets/c9fa1115-efa1-4b30-9fe6-107e448df910" />

## Qué es un lenguaje de programación?

Los lenguajes de programación como C# me permiten escribir instrucciones que yo quiero que el computador ejecute. Cada lenguaje de programación tiene su propia sintaxis, pero después de aprender mi primer lenguaje de programación y despues cuando quiera aprender otro, será fácil encontrar que estos comparten muchos conceptos similares. El trabajo de un lenguaje de programación es permitirle a un humano expresar sus instrucciones en un lenguaje legible por el humano y que este sea entendible. Las instrucciones que se escriben con un lenguaje de programación se llaman "código fuente" (Source code) o simplemente "Código". Eso es, en pocas palabras lo que hace un desarrollador de software: Escribir código.

Al escribir un código un desarrollador puede leer y actualizar el código, pero la computadora aún no puede entenderlo. Para ello, el código primero debe ser **compilado** en un formato que la computadora pueda entender.

## ¿Qué es una compilación?

Un programa especial, llamado un **compilador** convierte mi código fuente en un formato diferente que el procesador del computador central (CPU) puede ejecutar.

Por qué mi código necesita ser compilado? Si bien la mayoría de lenguajes de programación parecen crípticos al principio, estos pueden ser más o menos entendibles para los humanos, o por lo menos más legibles que el lenguaje preferido de la computadora. La CPU entiende instrucciones que estan expresadas a través de millones de interruptores brincando en On y Off a toda velocidad. Los compiladores funcionan entonces como puentes entre estos dos mundos traduciendo mis instrucciones hacia un computador. 

## ¿Qué es la sintaxis?

Las reglas para escribir en código C# se llaman **sintaxis**. Igual a como pasa con los lenguajes humanos, que tienen reglas acerca de la puntuación y estructura gramatical, los lenguajes de programación de computadoras también tienen reglas. Estas reglas definen cuales son las palabras clave y los operadores e C# y como ellos se deben poner juntos para formas aplicaciones.

## ¿Cómo funciona entonces un código?

Tomemos esta línea como ejemplo:

>Console.WriteLine("Hello World!");

Al ejecutar el código que escribí antes, pude notar que el mensaje "¡Hola Mundo!" se imprimió en la consola de salida. Cuando la frase está entre comillas dobles en tu código C#, se denomina cadena literal (Literal String). En otras palabras, querías que los caracteres H, e, l, l, o, etc., se enviaran literalmente a la salida.

>Console

Esta parte se llama una **Classes (Class)**. Las clases tienen métodos, o se podría decir que los métodos viven dentro de las clases. Para poder llamar al metodo primero debo especificar a qué clase pertenece. Por ahora puedo quedarme con que todos los métodos que tienen injerencia sobre la consola funcionan bajo la clase "Console"

>.

Luego viene el punto. Que separa el nombre de la clase llamado Console y el método llamado WriteLine(). el punto es el _Member access operator._ En otras palabras, el punto es como yo navego de la clase a uno de sus métodos.

>WriteLine()

Esta es, como ya he visto, la parte llamara _method_ o el método. Siempre se puede identificar un _method_ porque tiene un par de paréntesis después. Cada método tiene un trabajo. El método _WriteLine()_ tiene el trabajo de escribir una lineal de data en la consola de salida. La data que se imprime es especificada dentrod e los parentescos como un parámetro _input_. Algunos métodos necesitan ese parámetro adicional, otros no. Pero **siempre** que se llame a un metodo debo usar los paréntesis después del nombre. Estos paréntesis son conocidos como _method invocation operator_

>;

Finalmente el punto y coma es el _end of statement operator_ Un _Statement_ es una instrucción completa en C#. El punto y coma le dice al compilador que ah termina de entrar el comando especifico.

## Creando un nuevo proyecto.

Un proyecto de C# es una combinación de dos cosas. La primera es mi _Source code_ C# con instrucciones que yo escribo en C# para que la computadora las ejecute. La segunda parte es la configuración, instrucciones adicionales que le doy al computador para ayudarlo a saber como debe compilar o traducir el código C# en instrucciones de código binario que el computador pueda correr. Ambas partes viven en simples archivos de texto en mi computadora. **Los _Source Codes_ de C# usan la extensión .CS** en cambio una configuración de proyecto usa la extensión **.csproj**. Teniendo en cuenta que estos son simples archivos de texto, yo podría crearlos manualmente si así lo necesito.

Aunque usualmente lo mejor es comenzar con un Template, que ya trae algún código preparado para trabajar, en VS code se puede hacer con _Crtl+shift+P_

>_Crtl+shift+P_

Muchas de las aplicaciones que desarrollarás en C# requerirán que trabajes con datos. A veces, esos datos estarán codificados directamente en tu aplicación. Los valores codificados directamente son valores que permanecen constantes e inalterables durante la ejecución del programa. Por ejemplo, es posible que necesites imprimir un mensaje al usuario cuando una operación se complete con éxito. Un mensaje de "éxito" probablemente sería el mismo cada vez que se ejecute la aplicación. Este valor codificado también se conoce como constante o valor literal. Supongamos que deseas mostrar un mensaje formateado al usuario final que contenga diferentes tipos de datos. El mensaje incluiría cadenas de texto codificadas directamente, combinadas con información que tu aplicación recopila del usuario. Para mostrar un mensaje formateado, necesitarás crear valores codificados directamente y definir variables que puedan almacenar datos de un tipo específico, ya sean numéricos, alfanuméricos, etc.

