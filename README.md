### Repository Name

`opengl-rocket-controller`

### Description

Interactive 2D rocket simulation built with C++, OpenGL, and GLUT, demonstrating real-time geometric transformations, keyboard controls, and foundational computer graphics concepts.

# OpenGL Rocket Controller

A C++ computer graphics project that demonstrates the implementation of a real-time interactive 2D rocket using OpenGL and GLUT.

The application was developed to explore core graphics programming concepts, including geometric modeling, rendering pipelines, coordinate systems, transformations, event handling, and user interaction.

The rocket is entirely constructed from primitive OpenGL shapes and can be controlled through keyboard inputs, allowing users to apply translations and rotations in real time.

## Preview

This project renders a simple 2D rocket composed of multiple geometric primitives:

* Triangular nose cone
* Rectangular body
* Symmetrical side fins

Users can manipulate the rocket's position and orientation within the scene using keyboard commands, providing a practical demonstration of transformation matrices and interactive graphics programming.

## Features

* Real-time 2D rendering with OpenGL
* Keyboard-controlled movement system
* Translation transformations
* Rotation transformations
* Combined movement and rotation controls
* Orthographic projection setup
* Event-driven rendering with GLUT
* Simple and lightweight architecture for learning graphics fundamentals

## Controls

| Key       | Action                       |
| --------- | ---------------------------- |
| W         | Move Up                      |
| S         | Move Down                    |
| A         | Rotate Left                  |
| D         | Rotate Right                 |
| Q         | Move Up and Rotate Left      |
| E         | Move Up and Rotate Right     |
| Space     | Additional rotation maneuver |
| Shift + W | Turbo upward movement        |

## Technical Concepts Demonstrated

This project serves as a practical introduction to several fundamental Computer Graphics concepts:

* OpenGL rendering pipeline
* Primitive-based object construction
* Orthographic projection
* Matrix transformations
* Translation operations
* Rotation operations
* Coordinate systems
* Event-driven input handling
* Real-time graphical updates

## Technology Stack

* C++
* OpenGL
* GLUT (OpenGL Utility Toolkit)

## Project Structure

```text
.
├── tp1-cg-foguete.cpp
├── compile.sh
└── README.md
```

## Requirements

Before building the project, ensure the following dependencies are installed:

### Linux (Ubuntu/Debian)

```bash
sudo apt update
sudo apt install freeglut3-dev
```

### Fedora

```bash
sudo dnf install freeglut-devel
```

### Arch Linux

```bash
sudo pacman -S freeglut
```

## Building

If the provided build script is executable:

```bash
chmod +x compile.sh
./compile.sh
```

Alternatively, compile manually:

```bash
g++ tp1-cg-foguete.cpp -o rocket \
-lGL \
-lGLU \
-lglut
```

## Running

After compilation:

```bash
./rocket
```

A window will open displaying the rocket and enabling keyboard interaction.

## Educational Purpose

The primary objective of this project is educational. It was developed as part of Computer Graphics studies to provide hands-on experience with OpenGL fundamentals and interactive rendering techniques.

Although intentionally simple, the project demonstrates essential concepts that form the foundation for more advanced graphics applications, simulations, games, and visualization systems.
