# MJ_rotation_project
Rotation project in the Johnson lab, Spring 2021

The project focused on simulation of particle diffusion and intereaction. Particles were modelled as randomly diffusing through 3D space. Particles are able to bind to each other, forming particle particle pairs, and are also able to bind to a 1D object, initiating 1D diffusion.

Files 3D Walk V22.ipynb and 3D Walk V22.ipynb contain code. V22 is the most recent working version of the simulation, however it does not use physically relevant units of distance or time and binding/unbiding are handled through placeholder equations. V23 is an in-progress attempt at incorporating correct units of time and space and also of using more accurate equations to govern binding/unbinding behaviors. 

The four csv files are provided as an example of position and binding/unbinding probability information that is saved by the simulation at every time step. 

output.mp4 is a video demonstrating an implementation of the simulation. Particles of two different classes are colored red and purple. Green points represent bound pairs of particles, one from each class.


![grab-landing-page](https://github.com/andrew-bortvin/MJ_rotation_project/blob/main/particles.gif)
