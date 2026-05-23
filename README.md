# PID Line Follower Robot

A high-speed PID-based autonomous line follower robot built using a custom-designed IR sensor array with TCRT5000 sensors and differential motor control using the L298N motor driver.

## Overview

This project focuses on accurate and smooth line tracking using a PID (Proportional–Integral–Derivative) control algorithm.  
The robot continuously reads line position data from a custom-built IR sensor array and dynamically adjusts motor speed for stable navigation.

## Features

- Custom-built IR sensor array using TCRT5000 sensors
- Real-time PID control implementation
- Smooth differential motor speed control
- Fast and stable line tracking
- Oscillation reduction through PID tuning
- Designed for sharp turns and varying speeds


## Hardware Components

Arduino Nano 
TCRT5000 Sensors 
L298N 
N20 DC Motors 
Chassis (zero pcb)
Battery 

## Working Principle

1. The TCRT5000 sensor array detects the black line on a white surface.
2. Sensor readings determine the robot’s position relative to the line.
3. The PID controller calculates the error correction value.
4. Motor speeds are adjusted independently using the L298N driver.
5. The robot continuously self-corrects for smooth movement.


## Challenges Faced

  Sensor noise and false readings
  Motor speed imbalance
  Oscillation during sharp turns
  PID gain tuning


## Improvements Implemented

  Optimized sensor placement
  Differential speed correction
  PID parameter tuning
  Stable analog signal conditioning
