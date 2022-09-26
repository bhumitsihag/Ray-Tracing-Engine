# Ray-Tracing-Engine
Implemented a GPU accelerated Ray Tracer in CUDA C++ which can simulate effect of light on different shapes and materials like dielectric, metal and Lambertian and is able to produce videos of moving objects 12.7x faster than its CPU based counterpart.

This is a CUDA based Ray Tracing Engine.

Usage
Clone this repo and run make to compile. Use ffmpeg to compile the frames.

Current Capabilities
The engine can currently be used to simulate geometric objects with material types like Lambertian, metal, dielectric and diffuse light.

![image0](https://user-images.githubusercontent.com/86616792/192183605-6a1268b8-e0a0-48b8-a01e-bb8ff530c5ad.png)
![raytrace](https://user-images.githubusercontent.com/86616792/192183649-4e2352ef-13d2-4684-9da7-8ad776101c25.gif)

Requirements
Ensure CUDA toolkit 11.1 is used for compilation.

TODO

Implement monte carlo optimization.
Use trianglar meshes instead of equations.

Motivation
Im creating this project to get more familiar with ray-tracing.

Reference
Peter Shirley's Ray Tracing Guide
