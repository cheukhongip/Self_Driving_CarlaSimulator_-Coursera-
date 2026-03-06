# CARLA Waypoint Following Controller

This project is my final project for **Course 1 of the Self-Driving Cars Specialization in Coursera**.  
I implemented and tested a waypoint-following controller in **CARLA**, where the vehicle tracks a racetrack trajectory while following a target speed profile.

## Project Overview

The goal of this project is to control a simulated vehicle in CARLA so that it:

- follows the given racetrack waypoints
- tracks the desired speed profile
- generates trajectory and control outputs for evaluation

The controller was developed and tuned in Python using the provided course framework.

## Controller

For longitudinal control, I tuned a PID controller to provide stable and accurate speed tracking.

For lateral control, I implemented a waypoint-based steering controller to keep the vehicle aligned with the reference path and follow the racetrack smoothly.

## Results

The controller successfully completed the racetrack task and generated:

- vehicle trajectory output
- forward speed tracking plot
- throttle, brake, and steering plots

The speed tracking result showed that the vehicle was able to follow the reference speed reasonably well with only small lag and overshoot during speed changes.

## Demo Video


https://github.com/user-attachments/assets/d1f5d7ac-3109-49ea-ba15-0cda68b46f44



