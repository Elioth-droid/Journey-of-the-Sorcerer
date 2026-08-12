# Capítulo 0 "Git me a way Out"

Bueno, el primer paso es dominar las curiossas exentricidades de Git y Github antes siquiera de iniciar mi entendimiento arcano del lenguaje de programación.
Quisiera ser un poco más ordenado con estas notas pero haré mi mejor trabajo. Como siempre lo hago justo antes de fracasar.

**Github** es un repositorio virtual para proyectos de programación y **Git** es la herramienta de escritorio que se usa para administar estos proyectos dentro del almacenamiento local y luego quizá subirlos a Github.

> [!TIP]

Github es un editor de texto bastante pobre y poco intuitivo por lo que me dejo por aquí unos apuntes acerca de sus formatos para texto que tanto voy a necesitar.


>- Emphasis, aka italics, with `*asterisks* or _underscores_.`

>- Strong emphasis, aka bold, with `**asterisks** or __underscores__.`

>- Combined emphasis with `**asterisks and _underscores_**.`

>- Strikethrough uses two tildes. `~~Scratch this.~~`
 -------------

>- Emphasis, aka italics, with *asterisks* or _underscores_.

>- Strong emphasis, aka bold, with **asterisks** or __underscores__.

>- Combined emphasis with **asterisks and _underscores_**.

>- Strikethrough uses two tildes. ~~Scratch this.~~


## Notas de Git

>git commit

Primero lo más importante, hacer un **commit**. Un commit guarda una versión de mis cambios en el historial del repositorio local, dentro de mi maquina.

Se puede entender que es algo así como un checkpoint en mi proyecto.

>git branch [name]

Con esto se crea un nuevo branche con el name que yo le diga, un branch no es una copia es más bien como una referencia al proyecto principal (main)
y recuerda **"_Branchea_ temprano y _branchea_ a menudo"**

>git checkout [name]

El _checkout_ me permite indicarle a git sobre cual proyecto o rama estoy parado y cual deseo modificar o trabajar a continuación.

>git merge [name]

_Mergear_ en Git quiere decir crear un commir especial que tiene dos padres diferenes. Combinando los cambios de ambos padres y del conjunto de todos sus ancestros.
Lo unico que debo recordar por ahora es que el proyecto que tengo seleccionado (checkout) se va a mergiar con el branch que diga en el componente [name]

>git rebase (name)

Rebasear esencialmente agarra un conjunto de commits, los "copia", y los aplica sobre algún otro lado.

_merge_ une dos ramas conservando todo el historial y normalmente crea un commit adicional.

_rebase_ mueve tus commits para colocarlos después de los últimos cambios de otra rama. Sus ventajas son:

Produce un historial limpio y lineal.
Evita muchos commits de tipo “Merge branch…”.
Facilita leer cómo evolucionó el proyecto.

Me es difícil de entender en abstracto pero tratare de recordar esta advertencia que me dan:

>"La prohibición no es absoluta, pero mientras aprendes usa esta regla: nunca hagas rebase en main ni sobre commits que otras personas ya estén usando."

**HEAD** es el nombre simbólico del commit actualmente seleccionado -- es, básicamente, el commit sobre el que estás trabajando.


