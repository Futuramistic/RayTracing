# RayTracing
Ray Tracing project using GLSL. The project was developed for CS4247 (Graphics Rendering Techniques) at NUS.
To view the project, use https://www.shadertoy.com/new

## Task 1 - Basic Ray Tracing
<img src="https://github.com/Futuramistic/RayTracing/blob/master/Images/task1.PNG" style="vertical-align:middle" width="396" height="222"/>

### Basic Ray Tracing

Basic ray tracing. One ray is casted per pixel.
The scene consists of a silvery horizontal plane, a silvery vertical plane (in the background), a
bouncing golden yellow ball, and a revolving shiny green ball. There are two point light sources. The
image above was produced using 2 levels of ray tracing (recursion level = 2).

## Task 2 - Distributed Ray Tracing
<img src="https://github.com/Futuramistic/RayTracing/blob/master/Images/task2.PNG" style="vertical-align:middle" width="396" height="222"/>

### Distributed Ray Tracing with DOF effect

Distributed ray tracng. 32 rays casted per pixel. To simulate depth-of-field effect, each ray is randomly perturbed (using stratified sampling for subpixels) and collected on a "lens". 

## Additional tasks - glossy reflection and soft shadows
<img src="https://github.com/Futuramistic/RayTracing/blob/master/Images/soft.PNG" style="vertical-align:middle" width="396" height="222"/>

### Distributed Ray Tracing with soft shadows

Soft shadows are simulated by randomly perturbing position of light sources.
<img src="https://github.com/Futuramistic/RayTracing/blob/master/Images/glossy.PNG" style="vertical-align:middle" width="396" height="222"/>

### Distributed Ray Tracing with glossy reflection
Glossy reflection is simulated by randomly sampling a reflection ray origin from a normal surface of reflection point.
