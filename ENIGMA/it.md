ENIGMA, the **E**xtensible **N**on-**I**nterpreted **G**ame **M**aker
**A**ugmentation, is an [open source](open_source "wikilink")
[cross-platform](Cross_platform "wikilink") game development environment
derived from that of the popular software [Game
Maker](Game_Maker "wikilink"). Its intention is to provide you with a
quality game creation tool and a bridge between high- and low-level
programming languages. It can be used either through an
[IDE](Integrated_development_environment "wikilink"), namely, its sister
project, [LateralGM](LateralGM "wikilink"), or through a [Command line
interface](Command_line_interface "wikilink").

Like Game Maker, ENIGMA comprises both an easy to use [Drag &
Drop](Action "wikilink") system as well as its own programming language.
This programming language, known as [EDL](EDL "wikilink"), is
essentially a mix between [C++](C++ "wikilink") and Game Maker's
[GML](GML "wikilink"). Part of ENIGMA's goal is to remain backwards
compatible with Game Maker, serving for some intents and purposes as a
Game Maker compiler, however, EDL offers many very powerful features
which simply aren't present in the alternative. Such features include
the ability to compile DLLs and other C/C++ scripts right into the
program and access C++ types, templates, and functions.

Although EDL adopts GML's very lax syntax in its scripting, the inputted
code is actually parsed and translated into valid C++. This compilation
improves size and performance of the language by incredible amounts,
while almost magically maintaining its simplicity of use.

## Why Use Enigma Instead Of Game Maker

ENIGMA aims to be as compatible with Game Maker as possible. You can
load and save GM files in [LateralGM](LateralGM "wikilink"), then
compile them with ENIGMA. When ENIGMA's [function
set](Unimplemented_GM_Functions "wikilink") is finished it will have
practically all of Game Maker's capabilities, plus the following:

  - Speed improvements from an interpreted language to a compiled
    language. (For a basic counter loop you're looking at an increase in
    speed by a factor of about 150x)
  - Portability, having more available platforms and system options
  - Increased security of being compiled. It would be insanely difficult
    to decompile back to C++, and impossible to retrieve comments and
    variable names anyway
  - A reduction in starting size (Between 40 and 93 percent, depending
    on the platform)
  - The ability to create and access C++ types, templates, and functions
  - The ability to compile DLLs and other C/C++ scripts right into the
    program
  - Improved debugging
      - Access to a number of C/C++ classic debugging techniques (print
        to console)
      - Ability to use debuggers (gdb)
      - Access to the resulting C++ code
      - ENIGMA's built-in [Design Mode](Design_Mode "wikilink")
  - No YoYo Games. Which means it's:
      - Completely FREE
      - Open source
      - Has regular bug fixes
      - And developers actually listen to you
  - Many other improvements, additions, increased flexibility

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