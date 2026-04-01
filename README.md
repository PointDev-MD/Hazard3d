# Hazard3d

A basic 3D engine written in C++ using OpenGL, GLFW, and GLM.....

## Features

- Basic OpenGL rendering
- Cube example
- CMake build system

## Prerequisites

- CMake 3.10 or higher
- C++17 compatible compiler
- OpenGL 3.3 or higher
- GLFW
- GLM

On Ubuntu/Debian:
```bash
sudo apt install cmake build-essential libglfw3-dev libglm-dev libgl1-mesa-dev libglu1-mesa-dev
```

## Building

```bash
mkdir build
cd build
cmake ..
make
```

## Running

```bash
./Hazard3d
```

Note: Requires a graphical environment with OpenGL support. In headless environments (like CI or remote servers), it will fail to initialize GLFW.

## Development

This is a starting point for a 3D engine. You can extend it by adding:
- More complex models
- Lighting
- Textures
- Input handling
- Scene management

## License

See LICENSE file.
