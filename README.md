Here’s a **cleaned, corrected, and more professional README**, with the **YouTube demo added** and the **motor issue mentioned honestly but safely** (it won’t hurt you—this actually shows transparency and debugging awareness).

You can replace your current `README.md` with this:

---

# STM32 Line and Object Detection Robot

This repository contains an embedded systems project developed using an **STM32 microcontroller** and the **STM32 HAL library**. The project implements boundary detection and object avoidance for a mobile robot using onboard sensors and motor control.

## Demo Video

[![Project Demo](https://img.youtube.com/vi/mm-5keFU8P4/0.jpg)](https://youtu.be/mm-5keFU8P4)

## Project Overview

The robot operates inside a **rectangular area marked with a black boundary line**. Line sensors are used to detect this boundary and ensure the robot remains within the defined region. When the boundary is detected, the robot adjusts its direction to stay inside the area.

In addition to boundary detection, the robot includes **object detection** to prevent collisions. If an obstacle is detected in front of the robot, it changes its movement to avoid impact and then continues normal operation.

The project is implemented using the **STM32 HAL library** and focuses on low-level embedded programming, sensor interfacing, and real-time control logic.

## Features

* Black line (boundary) detection
* Rectangular area containment
* Object detection and collision avoidance
* Motor control using GPIO and PWM
* STM32 HAL-based implementation

## Hardware Used

* STM32 microcontroller
* IR-based line sensors
* Object detection sensor
* DC motors with motor driver
* Power supply / battery

## Software & Tools

* STM32CubeIDE
* STM32 HAL drivers
* C programming

## How It Works (High-Level)

1. Sensors continuously monitor the surface and surroundings
2. If a black boundary line is detected, the robot corrects its direction
3. If an object is detected ahead, the robot avoids it
4. Normal movement resumes once conditions are safe

## Notes

During testing, the **right motor was slightly jammed**, which caused minor imbalance during braking and while turning left or right. This affected motion symmetry but did not impact the overall functionality of boundary detection and obstacle avoidance.

## Purpose

This project was created as part of an **Embedded Systems course** to gain hands-on experience with STM32 microcontrollers, sensor integration, and control logic using HAL drivers.
