# Line Follower Robot

My first autonomous robot project. Built to understand how sensors, 
microcontrollers, and basic control logic work together.

## What It Does
Follows a black line on a white surface using an IR sensor array. 
Motors adjust speed based on sensor readings to stay centered on the line.

## Hardware
- Arduino Uno 
- IR sensor array 
- L298N motor driver
- 2x DC motors + chassis
- 7.4V battery pack

## What I Learned
- How IR sensors detect contrast (black vs white reflectivity)
- Basic motor control with PWM
- Why sensor placement and wheel traction matter
- Debugging hardware vs software issues (loose wires vs bad logic)

## Code Structure
- `line_follower.ino` — main logic, sensor reading, motor control
- [Add your actual files here]

## Notes
This was a learning project. The logic is simple (threshold-based or basic PID), 
but it gave me the foundation for the sensor fusion and control systems 
I used in later projects.
