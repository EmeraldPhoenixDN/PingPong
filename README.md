Pong 

Pong clone for Linux created with C++ and SDL 2.0.

The code uses the principles of OOP: encapsulation, inheritance, abstraction, and polymorphism. 
Also it uses some STL(e.g., pointers in most files).
Game has sound effects: paddle hit, wall hit and score update.
This software uses some libraries such as SDL 2, SDL Mixer, SDL TFT 2, cmath, random etc.
You will need:

- SDL 2.0(https://www.libsdl.org/)
- SDL Mixer 2.0(http://www.libsdl.org/projects/SDL_mixer/)
- SDL TTF 2.0(https://www.libsdl.org/projects/SDL_ttf/)

Install all dependencies on Ubuntu 16.04 and above:
`sudo apt-get install libsdl2-dev libsdl2-mixer-dev libsdl2-ttf-dev`

To get source:

git clone https://github.com/chaficnajjar/pong.git
cd pong
make

To play the game:

`./pong`

To play the game with joystick support:

./pong joystick

 Every program file is commented.

