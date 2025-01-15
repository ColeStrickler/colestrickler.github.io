layout: post
---

See full project and source code here: [VoxelEngine](https://github.com/ColeStrickler/voxel-engine).

This project is a graphics engine and it currently generates a voxel world with a chunk loading system similar to Minecraft. This is still an active work in progress that I try to upgrade when I have time. I am still quite an amateur when it comes to graphics programming but I find it highly challenging and enjoyable. 


This project entailed the following:
*   Learning and utilizing the OpenGL API
*   Utilizing ImGui to create a custom GUI framework for my engine
*   Creating an asynchronous logging and event system
*   Creating a performance profiling mechanism based on RAII paradigms
*   Creating an model loader to load blender models into the world
*   Writing various vertex, geometry, and pixel shaders for the graphics pipeline\
*   Writing a custom GPU memory allocator so we can render the entire world in a single draw call
*   Writing a renderer
*   Creating various Minecraft game mechanics such as placing blocks, chunk generation, ore generation, biomes, etc.


![voxelworld](/assets/img/voxel.png)