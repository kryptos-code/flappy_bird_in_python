* Creating a flappy bird game using Pygames

1. Making folders => flappy -> gallery -> audio, sprites
2. Creating a file => flappy -> main.py
3. Installing Pygame as => pip install Pygame
4. Now editing main.py file
    a) import modules.
    b) declaring Global Variables.
    c) setting SCREEN to display using pygame.
    d) initializing FPS_Clock using pygame.time.clock()
    e) initializing dictionary containing Sprites images as GAME_SPRITES
    f) initializing dictionary containing Audio as GaME_SOUNDS
    g) now declaring a while loop as True
    f) calling two functions => welcomeScreen() and then mainGame()

5. How pygame works?
    This module is used to load images and get their properties using various Methods in Pygame Module.
6. How to create Random Pipes?
    a) We need to load a single pipe image twice.
    b) Rotate first image to 180 degree to make it as upper pipe.
    c) Second image can be considered as the lower pipe.
