<link rel="preconnect" href="https://rsms.me/">
<link rel="stylesheet" href="https://rsms.me/inter/inter.css">

# MiniSwerve
![Swervepod2](assets/MiniSwerveDrawing.svg){ align=center }

![Swervepod2](assets/IMG_3590.png){ align=center }

## Our Drivetrain: What is swerve?

Generally any Swerve system refers to a wheel with 360° wheel steering. Our flavor of swerve is often called "differential swerve" refering to how the motors work together to orient, and drive the wheel. We'll update our sister site for software with more info on how we control this. 

## Big Picture: Swerve Robot

To create a comeptitive drive train, we put two identical Miniswerve 'pods' next to each other. Each of our swerve pods require two full size motors, and a classic mecanum drivetrain is 4 motors, so having 2 modules best mimics mecanum. 
Miniswerve is designed to be a cost comparable replacement for Mecanum, so not taking any more motors than absolutely neccesary is important: it lowers cost, complexity, and makes replacement of existing mecanum systems more accessible. 

But if Miniswerve is a Mecanum replacement, why bother with the added complexity?
Miniswerve should be better than a comparable mecanum drivetrain in a few ways: 

- [x] More Traction, no slip start
- - [x] Finer movement
- [x] Equal top speed & torque but in all directions (instead of a bias toward Left, right, forward, backward)
- [x] Faster turning on center
- [x] Higher Agility

## Drawbacks

Unfortunately there are some downsides, and we aren't here to hide them. So far we've struggled with: 

- [ ] Ground Clearance
- [ ] Ease of assembly
- [ ] Ease of manufacturing

Hopefully as a team we iterate we can eliminate or mitigate these issues, and perhaps teams that choose to develop evolutions of MiniSwerve will come up with unique ways to tackle these drawbacks too!

## From Concept to Robot

Miniswerve is our teams biggest accomplishment so far, even though its not finished. 
We've built two pods, gone through 3 hardware iterations, and began to tackle the enormous task of programming swerve. 

<figure markdown>
  ![firstdesign](assets/swervev1.png){ width="500" align="center"}
  <figcaption>April 13, 2022: Initial concept of gears, and choosing underlying ratios, much of this geometry is preserved in the final drawings. Also includes a 90mm mockup wheel. </figcaption>
</figure>

<figure markdown>
  ![firstdesign](assets/swervev2.png){ width="500" align="center"}
  <figcaption>April 15, 2022: Initial concept of mounting plates, first introduction of drive shafts and gears. This is where Miniswerve started to take form. On the same day, the definining difference for MiniSwerve was introduced: Thrust bearings. We'll have a whole section on this soon. </figcaption>
</figure>


## Today

MiniSwerve got its start early, and its taken a while to bring it to this point. It's been an awesome journey, and we made lots of progress. As of December, we are driving on the field with low downtime, and high reliability. 

If you are nterested in our progress, have questions, or have feedback on our design, don't hesitate to reach out to Hardware lead Grady Conwell at gconwell@lacanadaengineeringclub.org. 

![MachiningSwerve](assets/swervemachinepic1.png){ align=left }
Machining prototypes of the Swerve system. 

## Download the latest CAD
This is pulled right from Fusion, so it may be experimental or untested. But it should be the latest. Find releases of just the "swerve module" in its repo, here:  
[MiniSwerve](https://github.com/TheDragonlizard/MiniSwerve ){ .md-button .md-button--primary }

<iframe src="https://icloud11636.autodesk360.com/shares/public/SH35dfcQT936092f0e43955c17b2f02d9e36?mode=embed" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>


