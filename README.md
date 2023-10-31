# Projectile-Motion-Simulator APP

What is a Simple Projectile Motion?
Projectile motion is a motion in which the force that an object experiences is only force of gravity. Simple projectile motion is a projectile motion where we assume that air resistance is negligible, gravity vector has constant direction and magnitude, the projectile is relatively close to the surface of the Earth and its trajectory is relatively short

## Calculation
Users can change the mass, launch velocity, launch angle,
and launch height of the projectile and can calculate the height, horizontal range, or time of the projectile's trajectory as an output.

### Trajectory Time
This variable is calculated by way of the z-component of the projectile motion vector. We then solve for t using the quadratic
equation:
                  𝑧=−1/2 𝑔𝑡^2+𝑣_0𝑧 𝑡+𝑧_0<img width="380" alt="image" src="https://github.com/BezawitKassaye/Projectile-Motion-Simulator/assets/98127667/809bb5a8-9883-4d29-8a85-7af569b90ac8">

                  =(−𝑣0𝑧±√(𝑣0𝑧^2+2𝑔𝑧_0 ))/(−𝑔)<img width="374" alt="image" src="https://github.com/BezawitKassaye/Projectile-Motion-Simulator/assets/98127667/b3a354f6-c6a1-4454-8af4-d4747497b32a">



### Range
This variable is calculated by using the x-component of the projectile motion vector. We provide the trajectory time variable as an input:

                  𝑥𝑡 =𝑣"$𝑡+𝑥"

### Maximum Height

This variable is calculated by using the z-component of the
projectile motion vector. We find the maximum height by
providing the trajectory time as an input: Equation Reference:
  𝑧(𝑡) = − 1/2 g(t^2) 

              Equation Reference: 
              𝑣0𝑧 = 𝑣0𝑆𝑖𝑛θ
              𝑣0𝑥 = 𝑣0𝐶𝑜𝑠θ
              
## Creating the Interface
We developed an interface using the software Unity 2022.1.22, which is a product of a video game software development company. It works with Visual Studio Code serving as a platform to create our simulator, and it uses C# programming language.
The steps we took
1. We created objects to serve as the ground, the launch point, and the ball.
2. The ball was given code that allowed it to be launched in the direction of the mouse upon clicking the screen.
3. Its mass, launch angle, initial height, initial velocity and initial launch force were all made to be adjustable.
4. The launch point object was given code that would allow it to move up and down, changing the initial launch height. All variables, both dependent and independent, are recorded by text UI placed on the left side of the screen.

