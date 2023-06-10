# Robocon-2022

## Design of Seeker Robot 1 (Seeker R1)

![](https://github.com/Patil-Vinay/Robocon-2022/blob/main/R1_Robot_Design.png)

The Hopper-Funnel system on the Robot R1's body allows it to take all three balls from the Robot R2 at once. The middle of the three balls is loaded first, and the side balls, which will be used for reloading, are held in place by a hopper mechanism made up of two stepper motors. When the first ball is fired at the target lagori, the subsequent ones will be loaded one at a time.

Two linear actuators at the base plate of the Robot R1's body help lift the entire spinning body (the pipe-shooter mechanism) and offer an angle of elevation to it. The ball is then gently pushed towards the high-RPM motors, which mimic a baseball's mechanics, with the ball already loaded in the pipe-shooter.

## Design of Picker Robot 2 (Picker R2)

![](https://github.com/Patil-Vinay/Robocon-2022/blob/main/R2_Robot_Design.png)

We are utilising three suction cups and a vacuum to lift the lagori and move them to the lagori's square foundation. There are three suction cups: two facing down (Suction Cups 1 and 2), and one facing sideways (Suction Cup 3). Only the highest lagori will be lifted to the lagori pile using the sideways suction cup (Suction Cup 3). By placing these suction cups on the lagori, we will be producing a vacuum inside the suction cup, which will hold the lagori in place and release the vacuum when the vacuum is released. These linear actuators that can stretch outward are used to connect these suction cups to a platform. These platform-attached suction cups can move linearly up and down.
Stepper motors are used. The platform will move linearly upward using stepper motors when R2 approaches the lagori pile or lagori base, stopping at a height where lagori can be lowered to the pile. Lagori will be dropped by releasing the vacuum in the suction cup once the linear actuators have extended to the correct height and aligned the lagori directly above the lagori pile or lagori base.

We are utilising three suction cups and a hoover to pick up all three balls at once and move them to R1. To collect all three balls, the robot employs a vacuum pump to create a vacuum inside the suction cup that will hold the ball in place. All the balls will be released upon releasing the hoover. The platform, which can move linearly up and down using stepper motors, is joined to these three suction cups by linear actuators that extend outward. Stepper motors are used to move the platform linearly upward when R2 approaches R1, stopping at a height where balls may be dropped to the R1 feeder. The three balls will all be dropped by releasing the vacuum in the suction cup once the linear actuators have extended to the correct height and aligned the balls directly above the R1 feeder.

