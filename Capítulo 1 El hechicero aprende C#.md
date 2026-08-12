# Capítulo_1_El hechicero aprende C#

He comenzado con mucho temor mi viaje por el sendero de los lenguajes de programación. ya había tenido mis primero pinitos en JavaScript, pero siento que esto será un asunto completamente diferente.
Para esta sección estaré usando inciialmente el **curso fundacional de C# de Microsoft** (https://www.freecodecamp.org/learn/foundational-c-sharp-with-microsoft). 
De la mano con un libro que me recomendaron, el **CsharpPlayersGuide**. una lectura que no sé si tengo la autoridad de recomendar pero que yo he encontrado muy interesante.

Este mismo libro tiene esta útil grafica de progreso para ir midiendo mi nivel de poder en C#, así que le pedí a Chat GPT que me hiciera una versión para añadir a mi repositorio.

# Registro de experiencia en C#

Cada casilla representa **25 XP**. Cuando completes una unidad de experiencia, cambia `⬜` por `✅`.

| Progreso | XP para subir | XP total al completar | Casillas de experiencia |
|:--|--:|--:|:--|
| Nivel 1 → 2 | 200 XP | 200 XP | ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ ⬜ |
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
