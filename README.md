# MIPS Text-Based Adventure Game
## Overview
This is a text-based adventure game written in MIPS assembly language. The game takes the player through a series of choices in a dark, mysterious dungeon. The player must navigate through different corridors, make decisions, and interact with various objects and creatures to survive and escape the dungeon.

## Features
- Multiple Paths: The game offers multiple corridors and rooms to explore, each with unique challenges and outcomes.
- Interactive Choices: Players make decisions that affect the outcome of the game.
- Inventory System: Players can collect and use items such as a dull sword, a potion, and berries.
- Dynamic Storytelling: The narrative changes based on the player's choices, leading to different endings.

## How to Run
To run this MIPS program, you will need a MIPS simulator such as SPIM or MARS.
1. Download and Install a MIPS Simulator:
    - Download and install SPIM or MARS from the links provided above.
2. Load the Assembly File:
    - Open the simulator and load the .asm file containing the MIPS code.
3. Assemble and Run:
    - Assemble the code and run the program within the simulator.
4. Follow On-Screen Instructions:
    - The game will prompt you with text and choices. Input the corresponding numbers to make your decisions.

## Code Structure
The code is structured into different sections, each corresponding to a specific room or corridor in the game. The main sections include:

- Intro: The introduction to the game, setting the scene.
- Main Room: The central hub where players choose which corridor to explore.
- Left Corridor (LF): Contains a series of rooms with unique challenges.
- Middle Corridor (MD): Features encounters with monsters and items.
- Right Corridor (RT): Includes puzzles and traps.

### Variables
- $s0: Tracks the status of the dull sword.
- $s1: Tracks the status of the throwable potion.
- $s2: Tracks the status of the poison berries.
- $s3: Tracks the status of the dead cat.
- $s4: Tracks the status of the dark figure.

### Inventory System
- Dull Sword: Can be found in the Middle Corridor. Used to defend against monsters.
- Throwable Potion: Found in the Right Corridor. Can be used to defeat the dark figure.
- Poison Berries: Found in the Right Corridor. Can be used to feed the cat.
- Dead Cat: Obtained by feeding the cat poison berries. Used as a sacrifice.

## Endings
The game features multiple endings based on the player's choices. Some endings lead to survival and escape, while others result in the player's demise.

## Contributing
If you would like to contribute to this project, feel free to fork the repository and submit a pull request with your changes.

## Acknowledgment
This project is submitted in partial fulfillment of the requirements for CS222 Computer Architecture and Organization at the University of Science and Technology of Southern Philippines, June 2024.
