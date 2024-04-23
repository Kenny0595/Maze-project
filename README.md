# Maze-project
![images (10)](https://github.com/labaski/Maze-project/assets/123560218/18904a01-8a5b-4d3a-89e9-14626ab86f51)
![images (11)](https://github.com/labaski/Maze-project/assets/123560218/8fb8b964-9cc9-4e7f-8cf9-4dc7129d1485)
![images (12)](https://github.com/labaski/Maze-project/assets/123560218/f472509b-ce9c-4492-8b60-56dd95da983b)
![images (13)](https://github.com/labaski/Maze-project/assets/123560218/f7274ec9-aa5d-4de0-b4a8-09a11417e6e7)
![download (1)](https://github.com/labaski/Maze-project/assets/123560218/4c5ff2a9-a9b6-492d-974e-d50494f76fb2)

A 3D Maze game in .C codes by labaski james.
# MAZE GAME PROJECT

The Maze is a 3D Maze game that uses ray casting to render a 2D map into a 3D navigable world!

The Maze was written was written in C ussing SDL2 library. Deveploment was performed using Ubuntu 14.04 LTS - gcc (Ubuntu 4.8.4-2ubuntu1~14.04) 4.8.4

### About SDL2 

Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is used by video playback software, emulators, and popular games including Valve's award winning catalog and many Humble Bundle games.

## Instalation 
```sh
$ git clone https://github.com/Ad3b1y1/Maze-project.git
```
## Usage 
* Execute ./maze or type make run 
* Use up and down arrow keys to move forward and backward (keys w and s serve the same function)
* Use right and left arrow keys to turn the camera arround (keys d and a serve the same function)

## Compilation
```sh
$ gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze `sdl2-config --cflags` `sdl2-config --libs`;
```

## Flowchart
![The Maze Flow Chart]
(https://viewer.diagrams.net/index.html?tags=%7B%7D&highlight=0000ff&layers=1&nav=1&title=image.png#G183IjEStvA3ShZ1mOLezyWUIuknCo1LZu#%7B%22pageId%22%3A%22yHmmhTqG7p4PbAuGLyZZ%22%7D)

## Demo
[![The Maze Demo]
(https://m.youtube.com/watch?v=tnc1IY7nN7g)
