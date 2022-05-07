# CSE241-Final-Project
## Project Overview
- Summary of what the project is.
- ####  Explanation of the design ####
We are implementing the functionality of traffic lights. These traffic lights only have red and green (No yellow). There is one highway and one country road which intersect perpendicularly, the traffic is unidirectional on both of these roads. Both signals cannot be green at the same time to avoid collisions, but can be red. There are three sensors that decides the color of the light, Counting sensor, which counts the number of cars passing through when its on. Weather sensor lets you know if it is snowing or not and Enable sensor. When the enable sensor is off the lights will be red and when its on the lights will be green. Counting sensor counts the vehicals passing through when the light is green and the enable sensor is on. This counting sensor won't be working when its snowing. When the lights are changing from one color to another both the signals should be red to avoid collisiosns.

## Background Concepts
- List off what concepts are being utilized
## Tools and Resources
- BOM
- Software
- Equipment
## Design
- State diagram*
- Explanation of considerations and reasoning to develop the state diagram*
- State Table
- State Assignments
- Transition/Excitation Table
- Transition/Excitation Equations
- Output Equations
- Schematic
- System Verilog
  - Design file
  - Testbench file
## Testing
- Instructions to test physical implementation and using SV
## Synthesis Results
## Simulation Results
## Future Recomendations and Improvements
## References and Resources
- This project was designed and implemented by Hema Bobba in Spring 2022 for CSE241 at the University at Buffalo. Content in this repository is not to be reproduced or utilized without written authorization from the instructor, Dr. Winikus (jwinikus@buffalo.edu). 
