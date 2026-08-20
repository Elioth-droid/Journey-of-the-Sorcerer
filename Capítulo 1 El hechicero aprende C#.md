# Capítulo_1_El hechicero aprende C#

He comenzado con mucho temor mi viaje por el sendero de los lenguajes de programación. ya había tenido mis primero pinitos en JavaScript, pero siento que esto será un asunto completamente diferente.
Para esta sección estaré usando inciialmente el **curso fundacional de C# de Microsoft** (https://www.freecodecamp.org/learn/foundational-c-sharp-with-microsoft). 
De la mano con un libro que me recomendaron, el **CsharpPlayersGuide**. una lectura que no sé si tengo la autoridad de recomendar pero que yo he encontrado muy interesante.

Este mismo libro tiene esta útil grafica de progreso para ir midiendo mi nivel de poder en C#, así que le pedí a Chat GPT que me hiciera una versión para añadir a mi repositorio.

## Registro de experiencia en C#

Cada casilla representa **25 XP**. Cuando completes una unidad de experiencia, cambia `⬜` por `✅`.

| Progreso | XP para subir | XP total al completar | Casillas de experiencia |
|:--|--:|--:|:--|
| Nivel 1 → 2 | 200 XP | 200 XP | ✅ ✅ ✅ ✅ ✅ ✅ ✅ ✅ |
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

### Qué es un valor literal?

Un valor _Literal_ es una constante que nunca cambia. Son valores que se deben entregar pero no se operan entre ellos de ninguna manera.

### Usar un carácter literal
 
Si solo se quiere que un solo carácter alfanumérico sea presentado en la pantalla, se puede crear un carácter literal _Char literal_ rodeando un solo valor alfanumérico en single quotes ('').

>Console.WriteLine('b');

Ahora bien, si en vez de usar single quites(') rodeara el carácter con paréntesis ("") crearía un _String Data Type_

_String_ se usa para presentar múltiples caracteres en pantalla.
_Char_ se usa siempre que se quiera mostrar un solo carácter (Sin cálculos asociados)

## Usar _Integer literals_

Si se quiere mostrar un número entero (Sin fracciones) en la consola de salida, se puede usar un **int literal**. el término int es la contracción para integer (Entero en la lengua de Macondo). A diferencia de otros métodos un _int_ no necesita un operador.

>Console.WriteLine (123);

## Usar _Floating-point literals_

Un número _floating point_ es un número que contiene algún decimal, por ejemplo 3.14159. C# soporta tres tipos de datos para representar números decimales: _Float_, _double_ and _decimal_. Cada tipo soporta varios grados de precisión. 

Float Type    Precision
----------------------------
float         ~6-9 digits
double        ~15-17 digits
decimal        28-29 digits

En este caso, precisión refleja el número de dígitos, más allá del punto decimal se son precisos.

>Console.WriteLine(0.25f);

Para crear un literal float, se añade la letra **f** después del numero. En este contexto la "F" es llamada un **sufijo literal**, el sufijo literal le dice al compilador que tu deseas trabajar con un valor del tipo _float_. Se pueden usar mayúsculas o minúsculas para un sufijo literal.

> [HINT!] Nota como el valor tipo _float_ es el menos preciso de todos, así que es mejor usar este tipo de data para fracciones fijas para evitar eorrores de computación inesperados.

>Console.WriteLine(2.625);

Para crear un _double literal_, solo se debe poner el número con su punto decimal. El compilador por defecto asume que el número es un doble cuando no tiene un sufijo literal.

Para crear un literal decimal, añade la letra m después del número. En este contexto, la m se denomina sufijo literal. El sufijo literal le indica al compilador que deseas trabajar con un valor de tipo decimal. Puedes usar una m minúscula o una M mayúscula como sufijo literal para un decimal.

## Usar _Boolean_ literals

Si lo que quiero es imprimir un valor representando si algo es _falso_ o _verdadero_, se puede usar un literal booleano.

El término bool significa booleano.

>Console.WriteLine(true);
>Console.WriteLine(false);

Una booleana literal representa la idea misma de verdadero o falso. Se usan muchas booleanas cuando queremos empezar a añadir decisiones lógicas a nuestra aplicaciones.

## Porque enfatizar tanto en los _data types_?

Los _Data Types_ juegan un papel central en C#. De hecho, el énfasis en los diferentes data types es una de las características principales de C# comparado con otros lenguajes de programación como JavaScript. Los diseñadores de C# creían que podían ayudar a los desarrolladores a evitar errores comunes de software al imponer tipos de datos específicos.

## Los _Data Types_ definen las capacidades.

Antes, se podía ver como _strings_ y _char_s fueron usados para "presentación" no para cálculos, si quisiera hacer una operación matemática de valores numéricos se deben usar valores como _int_ o _decimal_s. En cambio si un dato es usado solo para presentacion o manipulacion de texto, se debe usar un _string_ o un _char_

Supongamos que necesitas recopilar datos de un usuario, como un número de teléfono o un código postal. Dependiendo del país o región donde vivas, esos datos pueden consistir en _int_ numéricos. Sin embargo, dado que rara vez realizas cálculos matemáticos con números de teléfono y códigos postales, es preferible utilizar un tipo de dato _string_ al trabajar con ellos.

En resumen

string for words, phrases, or any alphanumeric data for presentation, not calculation
char for a single alphanumeric character
int for a whole number
decimal for a number with a fractional component
bool for a true/false value

## Declarar variables

Un _literal_ es literalmente un valor _hard-code_. los valores hard-coded sn valores que son constantes y no se cambian a lo largo de la ejecución del programa. Sin embargo, la mayoría de aplicaciones va a requerir trabajar con valores que aún no conocemos. En otras palabras, se necesita trabajar con datos que vienen del usuario, desde archivos a través del internet.

Cuando necesitamos trabajar con datos que **no son** hard-coded, es entonces que declaramos variables.

### Qué es una variable?

Una variable es un contenedor para almacenar un tipo de valor. Variables son importantes porque sus valores pueden cambiar, o variar, a lo largo de la ejecución del programa.

Las variables puede ser asignadas, leídas y cambiadas. Se usan variables para guardar valores que pretendemos usar en nuestro código.

El nombre de una variable es una etiqueta fácil de recordar que el compilador asigna a una dirección de memoria. Cuando quieras almacenar o modificar un valor en esa dirección de memoria, o cuando quieras recuperar el valor almacenado, simplemente usas el nombre de la variable que creaste.

### Declarar Variables

Para crear una nueva variable, primero debemos declarar el tipo de dato de dicha variable, y luego darle un nombre.

string firstName;

En este caso, estamos creando una nueva variable del tipo _String_ llamada _firstname_ Desde ahora, esta variable solo puede contener datos del tipo _string_.

Se puede escoger cualquier nombre, mientras que se adhiera a algunas reglas de sintaxis de C# para el nombrado de variables.

## Nombre de Variables y convenciones

Un desarrollador de software famoso dijo una vez "Lo más difícil del desarrollo de software es nombrar cosas". El nombre de una variable no solo debe seguir algunas reglas de sintaxis, si no que también debe ayudar a hacer el código más entendible para el ojo humano. 

Aquí hay algunas consideraciones importantes sobre los nombres de variables: 
- Los nombres de variables pueden contener caracteres alfanuméricos y el guion bajo. No se permiten caracteres especiales como el símbolo de almohadilla (#) ni el símbolo de dólar ($).
- Los nombres de variables deben comenzar con una letra o un guion bajo, no con un número.
- Los nombres de variables distinguen entre mayúsculas y minúsculas, lo que significa que `string Value;` y `string value;` son dos variables diferentes.
- Los nombres de variables no deben ser palabras clave de C#. Por ejemplo, no se pueden usar las siguientes declaraciones de variables: `decimal decimal;` ni `string string;`.

Hay algunas convenciones acerca del nombrado que ayudan a mantener variables legibles y fáciles de identificar.

- Los nombres de las variables deben usar el formato camel case, que consiste en usar una letra minúscula al principio de la primera palabra y una mayúscula al principio de cada palabra siguiente. Por ejemplo: string thisIsCamelCase;.
- Los nombres de las variables deben comenzar con una letra del alfabeto. Los desarrolladores usan el guion bajo para un propósito específico, así que intenta no usarlo por ahora.
- Los nombres de las variables deben ser descriptivos y significativos en tu aplicación. Elige un nombre para tu variable que represente el tipo de datos que contendrá.
- Los nombres de las variables deben ser una o más palabras completas unidas. No utilice contracciones ni abreviaturas, ya que el nombre de la variable (y, por lo tanto, su propósito) podría resultar confuso para quienes lean su código.
- Los nombres de las variables no deben incluir el tipo de dato de la variable. Es posible que encuentre alguna recomendación de usar un estilo como string strValue;. Esa recomendación ya no está vigente.

Aquí algunos ejemplos de declaracion de variables usando el tipo de dato que hemos visto hasta ahora.

>char userOption;

>int gameScore;

>decimal particlesPerMillion;

<bool processedCustomer;

## Declarar implicitly typed local variables

El compilador de C# trabaja en segundo plano para ayudarte a escribir tu código. Puede inferir el tipo de datos de una variable a partir de su valor inicial. En esta unidad, aprenderás sobre esta característica, denominada variables locales con tipado implícito.

>var message = "Hello world!";

En este ejemplo, se creó una variable _string_ usando la palabra clave `var` en lugar de `string`. La palabra clave `var` le indica al compilador de C# que el tipo de dato está implícito en el valor asignado. Una vez que se infiere el tipo, la variable se comporta como si se hubiera declarado con su tipo de dato real. La palabra clave `var` se usa para ahorrar pulsaciones de teclas cuando los tipos son largos o cuando el tipo es obvio por el contexto.

>var message = "Hello world!";

Debido a que la variable message se establece inmediatamente con el valor de cadena "Hello World!", el compilador de C# entiende la intención y trata cada instancia de message como una instancia de tipo string.

De hecho, la variable de mensaje es de tipo cadena y nunca se puede modificar. Por ejemplo, considere el siguiente código:

>var message = "Hello World!";
>message = 10.703m;

Si ejecutas este código, verás el siguiente mensaje de error.

CS0029: No se puede convertir implicitamente el tipo 'decimal' a 'string'.

Es importante comprender que la palabra clave `var` depende del valor que se utilicé para inicializar la variable. Si intentas usar la palabra clave `var` sin inicializar la variable, recibirás un error al compilar el código.

>[HINT!] Al principio, se recomienda que sigas utilizando el nombre real del tipo de dato al declarar variables hasta que te familiarices con el código. Usar el tipo de dato al declarar variables te ayudará a escribir código de forma más precisa y concisa.

debo recordar que en todo casi, si uso el sufijo al final de un valor, este es el que intrínsecamente le da a la variable su clase:

3       → int
3f      → float
3.0     → double
3.0f    → float

f / F	float	3.14f
d / D	double	3.14d
m / M	decimal	3.14m

## Volviento al tema de crear proyectos en Visual Code (Comunity)

Siempre asigna un buen nombre a tus proyectos. No recordarás qué hizo _ConsoleApp12_ dentro de dos semanas.
Para la ubicación, elige un lugar que puedas encontrar fácilmente. (La ubicación predeterminada está bien, pero no es muy visible, así que anótala).
También hay una casilla para colocar la solución y el proyecto en el mismo directorio. Para proyectos pequeños, recomiendo marcar esta casilla. Los programas (soluciones) más grandes pueden estar formados por varios proyectos. En estos casos, es conveniente colocar los proyectos en su propio directorio (carpeta) dentro del directorio de la solución. Sin embargo, para programas pequeños con un solo proyecto, es más sencillo colocar todo en una sola carpeta.

### Namespaces

Todos los métodos residen en contenedores como una clase, pero incluso la mayoría de las clases residen en otros contenedores llamados *espacios de nombres* (namespaces). Los espacios de nombres son herramientas puramente destinadas a organizar el código, pero resultan valiosos cuando se trabaja con cientos o miles de clases. La clase `Console` reside en un espacio de nombres llamado `System`. Si añadimos esto a nuestro mapa de código, el resultado es el siguiente:

<img width="295" height="251" alt="image" src="https://github.com/user-attachments/assets/1f15148c-3792-49ee-871b-77fea4e17452" />

### Base class library

El mapa completo de un programa podría verse algo como 'System.Console.WriteLine();' dónde system seria el macro método donde todo calza. pero este maá no esta completo, es solo una pequeña parte de un todo. a estas librerias se les llama el Base Class Library, no planteo por ahora verlas todas peri si las más fundamentales.

## Realizar un _basic string formatting_ en C#

Como desarrollador de software (Nivel 1 actualmente), necesitarás escribir código C# para combinar y formatear datos literales y variables para crear un nuevo valor. Ese valor podría mostrarse, guardarse en un archivo o enviarse a través de la red. Afortunadamente, C# ofrece muchas maneras de combinar y formatear datos. Supongamos que quieres mostrar la salida de una aplicación de línea de comandos que estás desarrollando. Quieres mostrar valores que incluyan texto literal, texto en variables, datos numéricos y datos textuales en otros idiomas. ¿Cómo lo formatearías correctamente para que el usuario pueda entender lo que tu aplicación le está comunicando?

## Character escape sequences

Un carácter de secuencia de escape es una instrucción para que el compilador inserte un carácter especial a la salida de mi _string_

En C# la secuencia de escape empieza con es la tecla slash invertido (\) seguida por el carácter que le da el escape.

>- \n Añade una nueva línea.
>- \t Añade una tabulación.
>- \" Me permite usar comillas dentro de un string literal sin que el compilador se confunda.
>- \\ Es por si necesito escribir un backslash por alguna razón. (Tiene que haber una forma más fácil de hacer esto).
>- \u Añadir un carácter especial por medio de su código Unicode

Esto entonces:

>Console.WriteLine("Generating invoices for costumer \"Contoso Corp\" ... \n");
>Console.WriteLine("Invoice: 1021 \t\tComplete!");
>Console.WriteLine("Invoice: 1022 \t\tComplete!");
>Console.Write("\nOutput Directory: \t");

Daría como resultado en la consola:

Generating invoices for costumer "Contoso Corp" ... 

Invoice: 1021 		Complete!
Invoice: 1022 		Complete!

Output Directory:

## Verbatim string literal.

Un _Verbatim String Literal_ va a mantener todos los espacios y caracteres que ponga sin la necesidad de usar el backlash de escape (Lo sabia!, si hay un metodo más facil)

>Para usar un verbatim solo debo añadir el arroba (@) antes de iniciar el string, osea antes de las comillas.

## Unicode escape characters

También se puede agregar caracteres codificados en cadenas literales utilizando la secuencia de escape \u, seguida de un código de cuatro caracteres que representa algún carácter en Unicode (UTF-16).

>[HINT!] Esto de los unicode no va a funcionar en la consola de windows y dependiendo de la plataforma en la que esté trabajando puede que tenga que usar el UTF-32 en vez del UTF 16. Es un tema complicado que merece ser revisado más adelante.

## Qué es una concatenación de Strings?

La concatenación de cadenas es un término técnico que se refiere a la combinación de dos o más _Strings_ de texto en una sola. A diferencia de la suma, el segundo valor se añade al final del primero, y así sucesivamente.

>"+" con este conector se concatenan varios strings en uno solo.

## Qué es una interpolación de Strings?

Si bien la concatenación de cadenas es sencilla y práctica, la interpolación de cadenas está ganando popularidad en situaciones donde se necesita combinar muchas cadenas literales y variables en un único mensaje formateado.

La interpolación de cadenas combina varios valores en una única cadena literal mediante una plantilla y una o más expresiones de interpolación. Una expresión de interpolación se indica con llaves '{ }'. Dentro de las llaves se puede colocar cualquier expresión de C# que devuelva un valor. La cadena literal se convierte en una plantilla cuando se le antepone el carácter '$'.

En otras palabras, en vez de usar este formato:

>string message = greeting + " " + firstName + "!";

Se puede usar esta form más consisa:

>string message = $"{greeting} {firstName}!";

Para combinar un verbatim literal con un sting interpolation puedo hacer lo siguiente

>$@ (en ese ordén)

