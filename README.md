 # MAZE RACE
### ALX Final Project
A 3d maze game made with C programming language using SDL 2.1 library and raycasting concept.
![textured_1](https://github.com/hicarrie/maze/blob/master/screenshots/textured_1.png)
-----

### How to Compile and Run
- [SDL2](https://www.libsdl.org/download-2.0.php) and [SDL2_image](https://www.libsdl.org/projects/SDL_image/) are required to compile and use this program
- Compile with `gcc 4.8.4` with the following flags:
    ``gcc -O2 -g -Wall -Werror -Wextra -pedantic -Isrc/headers *.c -lSDL2 -lSDL2_image -lm -o maze `sdl2-config --cflags --libs` `` OR `make -f Makefile`
- Run the maze: `./maze` or `./maze maps/<map_name>`
- Disable textures: `./maze no_tex` or `./maze maps/<map_name> no_tex`

![textured_3](https://github.com/JohnIdyu-github/maze-race/blob/master/screenshots/textured_4.png)
-----

#### Controls
- `W` : move forward
- `S` : move backward
- `A` : rotate camera left
- `D` : rotate camera right
- `Q` : strafe left
- `E` : strafe right
- `F` : toggle fullscreen
- `ESC` : quit

@ -27,10 +23,3 @@ A 3d maze game made with C programming language using SDL 2.1 library and raycas
- Enemies / obstacles / objects
- Maze goal that loads next map
- Rain

### Resources
- [SDL2 API](https://wiki.libsdl.org/CategoryAPI)
- [LazyFoo Beginning Game Programming](http://lazyfoo.net/tutorials/SDL/index.php)
- [Ray-Casting Tutorial For Game Development And Other Purposes by F. Permadi](http://permadi.com/1996/05/ray-casting-tutorial-table-of-contents/)
- [LodeV Raycasting Tutorial](http://lodev.org/cgtutor/raycasting.html)
- [Game Engine Black Book](https://www.amazon.com/Game-Engine-Black-Book-Wolfenstein/dp/1539692876)