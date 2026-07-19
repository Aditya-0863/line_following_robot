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

## Software
The base code logic was referred from online resources / tutorials and 
adapted to match my specific hardware setup. I modified the sensor 
thresholds, motor PWM values, and pin assignments through experimental 
tuning.

## What I Changed / Tuned
- Sensor threshold values for my floor surface and lighting conditions
- Motor speed constants to match my motor torque and battery voltage
- Pin configuration to match my wiring layout
- Added serial debug output to tune the robot live

## What I Learned
- How IR reflectivity sensors detect contrast (black vs white)
- Why the same code behaves differently on different hardware
- The difference between "code works" and "code works on MY robot"
- Foundation for sensor-based control systems used in later projects

## Files
- [line_following_robot.ino](line_following_robot.ino) — Main Arduino sketch
