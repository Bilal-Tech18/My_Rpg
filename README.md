# My RPG
My RPG is a video game developed in C using the CSFML library. This project was realized in collaboration with three other contributors.

![top_map](https://github.com/user-attachments/assets/44119b69-8e99-49d5-bbca-a03c44773ae7)

## Contributors

- [Bilal-Tech18](https://github.com/Bilal-Tech18)
- [nellyyng](https://github.com/nellyyng)
- [SloWayyy](https://github.com/SloWayyy)
- [Tahalani](https://github.com/Tahalani)

## Features

- Exploration of different types of maps (church, castle, etc.)
- Interactive combat system
- Inventory to manage items
- NPCs with scripts and dialogues
- Varied animations (loading, objects, etc.)
- Intuitive menus (pause, settings, etc.)
- Save and load progress
- Integrated sound effects and music

## Prerequisites



To compile and run this project, the following libraries must be installed:

- **CSFML** (Graphics, Window, System, Audio)
- Criterion** (for unit testing)


### CSFML installation on Ubuntu or Debian:

```sudo apt install libcsfml-dev```

### Criterion installation on Ubuntu or Debian:


```sudo apt install libcriterion-dev```

## Compiling and running

To compile the project, run the following command in the root directory:

```make```



## Launching the game

After compilation, launch the game with :

```./my_rpg```


## Unit tests

The project includes unit tests, executable with the following command:

```make tests_run```

Code coverage results will be generated in the unwanted folder.

## Project structure

The project is organized into several modules for greater readability and maintainability:

    animation/ : Animation management
    map/ : Game map management
    menu/ : Menu management (settings, pause, etc.)
    player/ : Player management
    pnj/ : Non-playable character management
    inventory/ : Inventory management
    fight/ : Fight management
    utils/ : Utility functions
    destroy/ : Resource cleanup
    tests/ : Unit tests
