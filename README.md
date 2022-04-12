# Modelling of Discrete Systems
This repository contains my solutions to the following handouts from Modelling of Discrete Systems course on AGH UST:

*Note: parts of the code were created by the teachers. Most often we were tasked with implementations of the algotighms and some UI changes*

# Lab 1 - Game Of Life and Rain

### Game of life

Classic cellular automaton problem.

Features:

- The user can place cells before and during the simulation
- The game of life has a couple of different rule sets that can be changed during the simulation

### Rain Simulation

Application creates a simple rain simulation using cellular automaton.

### Demo of the application:

<img src="GameOfLife/demo.gif" alt="demo" style="width:50%;" />

# Lab 2 - Sound Wave

### A simple sound wave simulation using a Cellular Automaton

There are three kinds of placeable cells:

- White cells - Create a sound wave in the first iteration and then disappear
- Red cells - Represent a wall that the sound can't pass
- Green cells - send out a sound wave periodically

### Demo of the application:

<img src="SoundWave/sample.gif" alt="demo" style="width:50%;" />

# Lab 5 - Simple Pedestrians

### A simple force field based pedestrian simulator using Cellular Automaton

Each of the exits creates a force field, which the pedestrian uses for navigating to it

Application supports 

- Moore's neighborhood
- Von Neumann's neighborhood

There are four kinds of  cells:

-  0 - White cells - Represent the Floor
- 1 - Red cells - Represent a wall
- 2 - Green cells - Each cell is an exit
- 3 - Blue cells - Pedestrian

### Demo of the application:

<img src="Pedestrians/imgs/demo.gif" alt="demo" style="width:50%;" />
