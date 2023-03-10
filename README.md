# img2strings
An art project, weaving an image from a continuous string. The original idea is not mine, but I consider my imlementation to be the state of the art in terms of appearance quality and running time. 

## Pytorch optimization
- Pytorch code calculates the optimal strings to recreate the image
- Fast running time: 10-50 seconds, depending on approximation quality (resolution is around 7000x7000 pixels)
- Implemented custom forward and backward layers
- Implemented my own Optimizer

<img src="projectImages/DavidSimulation.jpeg" height="400"> <img src="projectImages/DavidDone.jpeg" height="400">
<img src="projectImages/rockySimulation.jpeg" height="400"> <img src="projectImages/rockyDone.jpeg" height="400">

## Machine
Arduino based machine that weaves the string to create the image in the real world.
Closed loop control using stepper motors. Designed from scratch including 3d printed parts, code and electronics.

<img src="projectImages/DavidMachine.jpeg" height="400"> <img src="projectImages/rockyMachine.jpeg" height="400">

## Frontend app
Just a simple web app for running the optimization conviently from any phone or computer.

<img src="projectImages/app1.jpeg" height="569"> <img src="projectImages/app2.jpeg" height="569">
