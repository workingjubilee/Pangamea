# Pangamea
Experimental project in motion, created primarily with VanillaScript.

In a sentence:
Compositional text game world-assembly engine.

In a paragraph:
Games should be playable. Orphaned games are not. Game-world composition would allow certain kinds of games, generated in a compatible engine, to be playable, without requiring an orphaned game to be entirely finished, because its pieces can be reassembled as a subset of a larger game. This also allows easy modification via adding new characters, for instance. Extensibility to support variant genres can be implemented as custom libraries, though there will be an inherent bias to a presumed default genre.

The full explanation:
The goal of Pangamea is to be able to take two game environments, generated within the Pangamea specification, not as distinct programs but as "continents" that can be "converged" by the game engine to create an entire "world". This is primarily useful for games with looser narrative architectures that use self-contained or procedurally-generated stories that do not require full participation of the remainder of the setting, but this specification can conceptually allow for logical transposition of chaining story events between "continents" by exploiting the prominent use in game narratives of archetypes. The results may become somewhat dreamlike and fantastic, but that is not automatically a drawback when the genre is fantasy.

In order to achieve "continental convergence", a great deal of conceptual collision detection and handling must be developed, and the specification and the engine's implementation of it must be sufficiently ruthless as to prevent clumsy creators from somehow making totally incompatible world elements (there are many other engines if they want to do that). These two are related, as the better the collision handling and ability to overlay results upon collision rather than error, the more creators are incapable of causing Pangamea to crash.

Because this is an audacious project to engage in at all, much less as a current solo venture, the first and perhaps only project in this vein will be Pangamea "Scriptura" for text adventure games. Interactivity will be created through prescribed clickable words and buttons a la Twine, rather than using Zork-style "parser" logic. This helps in development because it means it is easier to channel and understand player activities and to eschew the frustration of "what's the verb?" guessing-games.

"Wow this is really ambitious as a project for a novice programmer, huh?"
Yes, well, that's why I don't plan on getting it done any time soon. This is a toy to tinker with over time. However, if I can assemble even a basic world out of the world-builder parts I want, then it will have been worth my time, probably. It will also help develop personal self-management on programming projects.

Project Roadmap:
- ~Make the repo~
- ~Draft the Readme~
- Write up self-management structure and identify adherence tools
- Study similar text adventure engines for inspiration (e.g. Twine2)
- Develop small horizontal-slice text adventure game (Sample1)
- Develop Sample2, an incomplete game
- Refactor Sample1 and Sample2 to experimental "continent" specifications
- Develop the "Pangamea" tool and achieve successful continental convergence
