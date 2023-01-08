<link rel="preconnect" href="https://rsms.me/">
<link rel="stylesheet" href="https://rsms.me/inter/inter.css">

# Lifter 

## Download the Latest CAD
(Pulled right from our team files, may be experimental). This file comes with everything you need to design around our Arm, and its claw: Pinchy. 
<iframe src="https://icloud11636.autodesk360.com/shares/public/SH35dfcQT936092f0e433ce4fa157145dd8c?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

## Why lift? 
This years goal for FTC is to move cones from the ground too the top of posts. Since we can't move the drivetrain upwards, we'll need something that can go vertically to get us there. We had a couple requirements: 
- The lifter had to be stiff, with little side to side play
- The lifter had use less than 4 motors, and less than 4 servos
- The lifter had to be repeatable, and have good accuracy
- The lifter need to be as fast as possible. 

## Arm R1: Linkages
Our original arm used linkages, inspired by those sweet desk lamps (see pictured). But we quickly learned that due to linkage overextension and backlash, it had a "dead-zone", an area where the arm was uncontrollable, and simply would flop around. Ultimately, we switched to direct driving the elbow joint rather than using a linkage. 
![pictureoflamp](assets/Lampdiagram.png){ align=left }

<figure markdown>
  ![gifofarmmoving](assets/LittleArm.gif){ width="300" }
  <figcaption>A demo of the motion this kinematic provides</figcaption>
</figure>

## Arm R2: Direct Drive
Our current arm gets its speed from 3 motors. Two high gearing motors at the base, or shoulder of the arm, and 1 faster motor at the elbow. Because the means the forearm, or B stage is changing rotation, we need a servo "wrist" or C stage to keep the claw parralell to the ground. 
- You might notice that our Elbow (B) joint uses 3d printed gears! We learned from MiniSwerve that plastic Gears made from ABS & Nylon performed excellent under load when designed to take advantage of anisotropic nature of 3d prints (stronger in certain directions, like a wood grain). So far the Elbow gears have held up to the rigor of competition, and we highly recommend using application specific 3d printed gears when you can!

## Pinchy R2: Dual Side, Low Cost Claw
Pinchy is our solution to grabbing cones. Pinchy has no custom metal components, only M3 fasteners, and is almost entirely 3d printed. Its also fully modular! With just 2 screws you can take Pinchy on or off the wrist (C) effector. 
We love Pinchy R2 because it has...
- [x] Good Grip
- [x] Low Cost
- [x] No CNC parts
- [x] Ideal Cone geometry with an 85° taper
- [x] Quiet Operation

## Project Goals
- [x] High stiffness 
- [x] Limited “linear motion” components
- [x] Low cost 
- [x] Easily sourced / made parts (as little CNC as possible).
- [x] High extension to weight ratio.
- [x] Modular
- [x] Easy to modify

## Keynote Features
- 19mm Square Aluminum Extrusion (16 gauge) Construction
    - This stuff is really good, requires no CNC machining for our use, can be easily fabricated by hand into the shapes we need. Its also super light: each link of the arm is less than 150g! You can also buy it at most hardware stores in the United States. 
- High Extension (and easily folded into 18" cube)
    - Our 2+1 joint setup lets us fold the arm back into the empty space above the chassis during the start of the game. We can then extend it forward, and upward to interact with cones. 

