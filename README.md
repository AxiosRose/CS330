# CS 330 – Computational Graphics and Visualization

This repository contains portfolio artifacts from **CS 330: Computational Graphics and Visualization** at Southern New Hampshire University.

The project artifacts demonstrate my work with C++, OpenGL, 3D transformations, textures, lighting, materials, and interactive camera controls. My final scene is a textured coffee mug placed on a wooden surface. I built the scene using reusable primitive meshes and then added materials, lighting, textures, and navigation controls to create a complete interactive 3D environment.

## Portfolio Artifacts

### 3D Scene

The `CS330_3D_Scene.zip` file contains the source files, Visual Studio project files, and texture assets for my final 3D scene.

The scene includes:

- A coffee mug built from primitive meshes
- A textured wooden surface
- Ceramic, glaze, wood, and coffee materials
- Multiple light sources
- Ambient, diffuse, and specular lighting
- Texture mapping
- Camera movement with keyboard controls
- Mouse-controlled viewing
- Perspective and projection handling

### Design Decisions

The `CS330_Design_Decisions_Final.docx` document explains the major design choices I made while building the scene, including geometry, texturing, lighting, camera navigation, materials, and code organization.

## Reflection

### How do I approach designing software?

This project helped me improve the way I break a larger visual problem into smaller pieces. Instead of trying to model the entire coffee mug as one complicated object, I built it from reusable primitive shapes such as cylinders and torus meshes. I used transformations to scale, rotate, and position those shapes until they created the final object. This helped me understand that a good software design does not always need to be complicated. Reusing smaller components can make a project easier to understand and change.

My design process started with the basic geometry and then added features in stages. I first made sure the shapes were positioned correctly, then worked on camera movement, textures, materials, and lighting. I kept responsibilities separated in the code so that scene setup, transformations, materials, lighting, and rendering were handled by different functions. This made it easier to troubleshoot because I could focus on one part of the scene without changing everything else.

I can use the same approach in future projects by breaking large problems into smaller components, keeping related responsibilities together, and building features in a logical order. This is useful outside of graphics as well because modular code is easier to test, maintain, and improve.

### How do I approach developing programs?

One of the biggest development strategies I used in this project was iteration. The scene did not reach its final form all at once. Each milestone added another part of the project, including object placement, camera controls, textures, and lighting. I would make a change, run the program, look at the result, and then adjust the code based on what I saw.

Iteration was especially important when I worked with textures and lighting. A material or light setting could be technically correct but still look wrong in the scene. For example, I had to adjust the ceramic lighting because the mug became too bright and lost visible detail. I also had to work through camera and mouse controls so that the scene could be explored from different viewpoints. Seeing the result after each change helped me understand how the different graphics settings affected one another.

My approach to developing code changed throughout the milestones because I became more comfortable making smaller changes and testing them before moving on. Earlier in the course, I focused mostly on getting a feature to work. By the end, I was also thinking about organization, reuse, appearance, and how one change could affect another part of the scene. That iterative process helped me reach the final project without having to rewrite the entire program at the end.

### How can computer science help me in reaching my goals?

Computational graphics gave me a better understanding of concepts that I had previously only seen in theory. Working with vectors, coordinates, matrices, transformations, lighting, and textures showed me how math and programming work together to create something visual. This will help in future computer science courses because I now have more experience working with larger C++ projects, debugging visual output, and understanding how data moves through a graphics pipeline.

Professionally, these skills are useful even if I do not work directly in game development or 3D graphics. The project strengthened my ability to work with unfamiliar libraries, organize a larger codebase, troubleshoot problems, and improve a program through repeated testing. Visualization is also important in areas such as data analytics, simulation, engineering, user interfaces, and software development. Understanding how visual information is created and controlled gives me another way to communicate data and ideas in future technical work.

## Technologies and Concepts

- C++
- OpenGL
- Visual Studio
- GLFW
- GLEW
- GLM
- 3D transformations
- Texture mapping
- Phong-style lighting
- Materials and shaders
- Camera movement and mouse controls
- Iterative development

## Course

**CS 330 – Computational Graphics and Visualization**  
Southern New Hampshire University
