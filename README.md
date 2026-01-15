# Line-Object-detection-Bot-Using-STM32
This project was developed using an STM32 microcontroller and the STM32 HAL library. 
This repository contains an embedded systems project developed using an STM32 microcontroller. The goal of the project is to implement boundary detection and object avoidance for a mobile robot using onboard sensors and motor control.

Project Overview

The robot operates inside a rectangular area marked with a black boundary line. Line sensors are used to detect this boundary and ensure the robot stays within the defined region at all times. If the boundary is detected, the robot adjusts its direction to remain inside the area.

In addition to boundary detection, the system also includes object detection to prevent collisions. When an obstacle is detected in front of the robot, it changes its movement to avoid impact and then continues normal operation.

The project is implemented using the STM32 HAL library and focuses on low-level embedded programming, sensor interfacing, and real-time control logic.

Features

Black line (boundary) detection

Rectangular area containment

Object detection and collision avoidance

Motor control using GPIO/PWM

STM32 HAL-based implementation

Hardware Used

STM32 microcontroller

Line sensors (IR-based)

Object detection sensor

DC motors with motor driver

Power supply / battery

STM32CubeIDE

STM32 HAL drivers

C programming

How It Works (High-Level)

Sensors continuously monitor the surface and surroundings

If a black boundary line is detected, the robot corrects its direction

If an object is detected ahead, the robot avoids it

Normal movement resumes once conditions are safe

Purpose

This project was created as part of an Embedded Systems course to gain hands-on experience with STM32 microcontrollers, sensor integration, and control logic using HAL drivers.
