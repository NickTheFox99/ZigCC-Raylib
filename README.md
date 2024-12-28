## Raylib Zig CC Template

This is a template I have modified for personal use, and found it to be useful and convenient, especially for cross-compiling.
The reason I made this was because I was having lots of trouble attempting to find a template that works for Raylib, so I decided to make my own.
It used raylib-gamejam-template to start, then it was built on to use Zig CC and Emscripten.

### Usage

This was built using VS Code, and is targeted to be used with VS Code. You need to install Zig, and build the Raylib source with Zig.
Put the built .lib into lib/raylib, and test the compiling.
Currently, the only way to build is using VS Code tasks (Debug Windows & Release Windows), and using the .bat for emscripten.