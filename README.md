# CS330
CS 330 Computational Graphics and Visualization portfolio project featuring a C++ and OpenGL 3D scene with textures, lighting, shaders, and interactive camera controls.

# CS 330 Computational Graphics and Visualization

## Project Overview

This repository contains my CS 330 Computational Graphics and Visualization project developed using C++ and OpenGL.

The project demonstrates the creation of a 3D scene using basic geometric shapes, textures, lighting, shaders, and interactive camera controls. The scene includes a textured coffee mug placed on a wooden surface and uses multiple lighting sources to create a polished 3D environment.

## Features

- 3D objects created from primitive shapes
- Texture mapping on multiple objects
- Phong lighting model
- Ambient, diffuse, and specular lighting
- Multiple light sources
- Material and shader properties
- Interactive camera movement
- Keyboard and mouse controls
- Perspective-based 3D rendering
- Modular and organized C++ code

## Controls

The scene can be explored using the keyboard and mouse:

- **W** - Move forward
- **S** - Move backward
- **A** - Move left
- **D** - Move right
- **Q** - Move down
- **E** - Move up
- **Mouse** - Change camera orientation
- **Mouse Scroll** - Adjust camera movement behavior/speed

## Technologies Used

- C++
- OpenGL
- GLFW
- GLEW
- GLM
- Visual Studio
- GLSL shaders

## Reflection

### How do I approach designing software?

When designing software, I begin by breaking the overall problem into smaller components. For this project, I separated the scene into individual objects, textures, lighting properties, camera controls, and transformations. This made it easier to develop and test each part independently before combining everything into the final scene.

Working on this project helped me improve my ability to think about software visually and spatially. I had to consider not only how the code worked, but also how objects were positioned, scaled, rotated, textured, and illuminated within a 3D environment.

### How do I approach developing programs?

I approach development iteratively. I first create a basic working version and then add functionality in smaller steps. During this project, I began with simple 3D shapes, then added camera navigation, textures, materials, and lighting.

Testing after each major change helped me identify problems before adding additional complexity. For example, I adjusted the lighting several times to prevent the ceramic mug from becoming overexposed while still keeping all parts of the scene visible.

I also used modular functions such as `PrepareScene()`, `RenderScene()`, `SetupSceneLights()`, `DefineObjectMaterials()`, and `SetTransformations()` to keep the code organized and easier to maintain.

### How can computer science help me reach my goals?

Computational graphics gave me additional experience working with C++, object transformations, shaders, textures, lighting, and interactive input. These skills reinforce important computer science concepts such as problem solving, modular design, debugging, mathematical reasoning, and working with external libraries.

The project also gave me experience building an interactive application rather than only working with text-based programs. Understanding how graphics systems process objects, cameras, textures, and lighting can be useful in areas such as software development, visualization, simulation, game development, and data visualization.

## Author

Daryl Spencer Rosenberry
