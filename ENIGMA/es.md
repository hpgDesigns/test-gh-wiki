ENIGMA, el Aumento Extensible No-Interpretado de Game Maker
(***E**xtensible **N**on-**I**nterpreted **G**ame **M**aker
**A**ugmentation* en inglés), es un entorno de desarrollo de videojuegos
[multiplataforma](Cross_platform/es "wikilink") de [código
libre](open_source/es "wikilink") derivado del popular software [Game
Maker](Game_Maker/es "wikilink"). Su intención es proveerte de una
herramienta de creación de juegos de calidad, y un puente entre los
lenguajes de programación de bajo y alto nivel. Puede ser usado a través
de un [IDE](Integrated_development_environment/es "wikilink")
particular; su proyecto hermano [LateralGM](LateralGM/es "wikilink"), o
a través de una [interfaz de línea de
comandos](Command_line_interface/es "wikilink").

Similar a Game Maker, ENIGMA posee tanto un sistema de [Arrastra y
Suelta](Action/es "wikilink") de fácil uso, como su propio lenguaje de
programación. Este lenguaje de programación conocido como
[EDL](EDL/es "wikilink"), es, esencialmente, una mezcla entre
[C++](C++/es "wikilink") y [GML](GML/es "wikilink") de Game Maker. Una
parte del objetivo de ENIGMA es poseer compatibilidad con versiones
anteriores de Game Maker, sirviendo para tales funciones como un
compilador de Game Maker. Sin embargo, EDL ofrece muchas y poderosas
características que simplemente no están presentes en el alternativo.
Entre éstas se incluyen la habilidad de compilar DLLs y otros scripts de
C/C++ directamente dentro del programa, y acceder a estilos, funciones y
plantillas de C++.

Aunque EDL adopta la baja exigencia del sintaxis de scripting de GML, el
código introducido es de hecho re-codificado, y traducido en C++ válido.
Esta compilación disminuye el tamaño y aumenta la performance del
lenguaje en cantidades impresionantes, mientras que mantiene su
simplicidad como por arte de magia.

## Porqué utilizar ENIGMA en vez de Game Maker

ENIGMA busca ser tan compatible con Game Maker como sea posible. Puedes
abrir y guardar archivos GM en LateralGM, e incluso compilarlos con
ENIGMA. Cuando [el set de
funciones](Unimplemented_GM_Functions "wikilink") de ENIGMA esté
finalizado, poseerá prácticamente todas las capacidades de Game Maker,
además de lo siguiente:

  - Mejoras de velocidad desde un lenguaje interpretado a un lenguaje
    compilado (para un simple ciclo de código, estarías mirando un
    incremento de 1500%).
  - Portabilidad, poseyendo compatibilidad con varias plataformas y más
    opciones de sistema.
  - Mayor seguridad en la compilación. Sería increíblemente difícil
    decompilar de vuelta a C++, e imposible sustraer los comentarios y
    nombres de variables, de todas maneras.
  - Una reducción del tamaño de los proyectis (entre 40 y 93 por ciento,
    dependiendo de la platforma).
  - La habilidad de acceder a estilos, funciones y plantillas de C++.
  - La habilidad de compilar DLLs y otros scripts C/C++ directamente en
    el programa.
  - Mejoras en la depuración
      - Acceso a varias técnicas clásicas de depuración de C/C++ (en
        consola).
      - El uso de depuradores (gdb).
      - Acceso al código C++ resultante.
      - ENIGMA's built-in [Design Mode](Design_Mode "wikilink")
  - No hay YoYo Games por entre medio. Lo cual significa que:
      - Es completamente GRATIS.
      - Es de código abierto.
      - Posee arreglos de errores regulares.
      - Y los desarrolladores te prestan atención
  - Y muchas otras mejoras.

## Why Use Enigma Instead Of C++

ENIGMA offers some major benefits from just using C:

  - A prebuilt engine to base your creations off of, and a simple
    interface which accepts C/C++ code.
  - High level functions, and variables with variant datatypes. Arrays
    with no risks of overflow.
  - Resources are included for you in the engine, no additional work is
    required to load them.
  - Lax syntax and a friendlier typing system. Semicolons aren't
    required, templates don't require parameters, and var can represent
    strings or numbers.
  - Much greater ease of use, especially for those with little
    programming knowledge, allowing you to learn the logics of
    programming under a practical game development environment.

Understand, of course, that the processes ENIGMA takes to handle
instances and resources may be slower than a custom engine in pure C++.
Much care has been put into each system, however, and in the end, the
differences will most likely prove insignificant. In any case, our goal
is to have the simplicity the system offers justify any speed reduction.
Options will exist for further optimization, such as variables that some
may find a waste of space being removable.

Data types are dynamic if undeclared, but unlike in Game Maker, you will
be able to declare something you do not plan to change as one byte. Or a
short, double, string; whatever you like for optimal performance. This
way, it will use less memory if you declare it yourself, but you will be
able to switch between data types if you do not specifically declare it.

## Proof

Want some proof of ENIGMA's prowess? Try some of our games:
<http://enigma-dev.org/edc/games.php?action=list>

Note that most of these game were made in Game Maker, but ENIGMA can
directly compile Game Maker games so they run a lot faster\! Most of
these games could also be made even faster by taking advantage of
ENIGMA's extra features such a type casting and control over the
internal mechanisms.

## The ENIGMA Team

ENIGMA is developed and maintained by a growing number of individuals.

__NOTOC__