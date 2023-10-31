# Projectile-Motion-Simulator APP

What is a Simple Projectile Motion?
Projectile motion is a motion in which the force that an object experiences is only force of gravity. Simple projectile motion is a projectile motion where we assume that air resistance is negligible, gravity vector has constant direction and magnitude, the projectile is relatively close to the surface of the Earth and its trajectory is relatively short

## Calculation
Users can change the mass, launch velocity, launch angle,
and launch height of the projectile and can calculate the height, horizontal range, or time of the projectile's trajectory as an output.

### Trajectory Time
This variable is calculated by way of the z-component of the projectile motion vector. We then solve for t using the quadratic
equation:

<img width="200" alt="image" src="https://github.com/BezawitKassaye/Projectile-Motion-Simulator/assets/98127667/55a9b42f-4b9e-4839-8b48-cbcbe5963586">




### Range
This variable is calculated by using the x-component of the projectile motion vector. We provide the trajectory time variable as an input:


<img width="200" alt="image" src="https://github.com/BezawitKassaye/Projectile-Motion-Simulator/assets/98127667/fdc3279f-4dcc-41a7-8ef9-f8485be1c40d">
 

### Maximum Height

This variable is calculated by using the z-component of the
projectile motion vector. We find the maximum height by
providing the trajectory time as an input: Equation Reference:

<img width="200" alt="image" src="https://github.com/BezawitKassaye/Projectile-Motion-Simulator/assets/98127667/2ba5ecf9-f240-4f9a-83c4-b412f91bcf1b">

<img width="200" alt="image" src="https://github.com/BezawitKassaye/Projectile-Motion-Simulator/assets/98127667/71d466a1-9e8f-48e5-893f-602aaad02c7d">

              
## Creating the Interface
We developed an interface using the software Unity 2022.1.22, which is a product of a video game software development company. It works with Visual Studio Code serving as a platform to create our simulator, and it uses C# programming language.
The steps we took
1. We created objects to serve as the ground, the launch point, and the ball.
2. The ball was given code that allowed it to be launched in the direction of the mouse upon clicking the screen.
3. Its mass, launch angle, initial height, initial velocity and initial launch force were all made to be adjustable.
4. The launch point object was given code that would allow it to move up and down, changing the initial launch height. All variables, both dependent and independent, are recorded by text UI placed on the left side of the screen.

