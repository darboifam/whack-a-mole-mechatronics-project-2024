# Pneumatic Whack-a-Mole

## Overview
This project was a senior-year mechatronics build that I completed in 2024 at North Montco Technical Career Center. The goal was to create a functional whack-a-mole game using pneumatic cylinders, solenoid-actuated directional control valves, custom 3D-printed moles, and an Arduino Uno for random game logic.

## Original Plan
My original idea was to use an Allen-Bradley SLC 500 PLC that was available in my mechatronics lab. The PLC would control the pneumatic cylinders that raised and lowered the moles. After thinking through the gameplay, I realized a PLC-based sequence would likely be too predictable and that players could learn the pattern too quickly.

## Design Pivot
To make the game more random and exciting, I switched from the PLC to an Arduino Uno. This gave me much more flexibility for game logic and random actuation. The downside was that I had very little coding experience, so I had to learn the Arduino IDE, work with C/C++ style Arduino code, adapt starter code, and troubleshoot the system as I built it.

## Mechanical Design
The moles were 3D printed and designed with a cavity in the body to hold a limit switch. The head had a hinged cap that rested on the actuator arm and pressed the switch when actuated. This let the design combine mechanical motion with electrical feedback.

## Housing and Fabrication
I also had to figure out how to build the physical housing for the game. I first considered drywall, but it was not a good material for fastening panels together with screws. After researching and speaking with instructors, including the carpentry teacher, I chose plywood instead.

## Layout Decisions
Another design challenge was deciding how many moles to include and how to arrange them. I considered a row of 4 and then a row of 5, but I eventually settled on a 5-mole layout based on the pattern of the five side of a die.

## What I Learned
This project taught me how to adapt a design when the original control approach was not the best fit, how to learn new tools quickly, how to troubleshoot software and hardware together, and how to make better engineering decisions through research and instructor feedback.

## Main Components
- Arduino Uno
- Pneumatic cylinders
- Solenoid-activated directional control valves
- Limit switches
- 3D-printed mole assemblies
- Plywood housing

## Files
This repository will include photos, design files, code, and documentation related to the project.
