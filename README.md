# World of Zuul – Text Adventure Game (Java)

> A story-driven text adventure with an inventory system, moving NPCs, three-word commands and a teleporting "magic room".

🔒 **The source code is in a private repository** because this was university coursework at King's College London. I'm happy to walk through the code on request.

## Overview
I extended a basic text-adventure framework into a complete game with a setting, a story and a clear win condition. The player explores rooms, collects and uses items, and interacts with characters through a text command parser. The game is distributed as a runnable JAR.

## Features
- Six or more interconnected locations, with items that are either collectable or fixed in place
- A player inventory with a weight limit
- A `back` command that retraces all previous moves using a movement-history stack
- At least four new commands for items and the game's mechanics
- **Challenge features:** NPCs that move between rooms, a parser extended to handle three-word commands (e.g. giving an item to a character), and a magic transporter room that sends the player to a random location

## Skills demonstrated
Object-oriented design · command parsing · data structures (stacks, collections) · game logic

## Tech stack
Java · BlueJ
