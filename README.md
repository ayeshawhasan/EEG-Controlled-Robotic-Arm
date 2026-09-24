# EEG-controlled robotic arm
EEG-controlled robotic arm is a prototype developed using Arduino Uno R3, C++, and embedded electronics to explore affordable assistive technology. This repository documents the project's development, execution and my technical contributions to the embedded software and hardware integration.

## Project Overview
The project explores the use of EEG (electroencephalography) signals as an input for controlling a robotic arm. The prototype focuses on detecting changes in brainwave activity associated with deliberate eye blinks and translating these signals into commands for a servo-controlled robotic arm.
The project was developed as a proof-of-concept for how accessible embedded electronics and signal processing could contribute to assistive technologies for individuals with limited motor control.

## Objectives
The main objectives of the project were to:
*Develop a functional EEG-controlled robotic arm prototype
*Capture and process EEG signals using an Arduino Uno R3
*Identify signal changes associated with deliberate eye blinks
*Convert detected signals into control commands
*Control the movement of a robotic arm using servo motors
*Explore the potential of low-cost electronics for assistive technology
*Test the reliability of the system through recorded EEG signals and physical responses

## Hardware
The main hardware used in the prototype includes:
*Arduino Uno R3
*EEG sensor/electrodes
*Servo motors
*Robotic arm frame
*External battery power supply
*jumper wires
*Breadboard and electronic components

## Software
The embedded software was developed in C++ using the Arduino IDE.
The program is responsible for:
 *Reading EEG signal data
 *Sampling incoming signal values
 *Processing the recorded signal
 *Identifying changes associated with deliberate blinks
 *Applying programmed detection thresholds
 *Controlling the servo motors
 *Producing the corresponding robotic arm movement

## Project Outcome
The testing demonstrated the feasibility of using detectable EEG signal changes as an input for controlling a simple robotic mechanism.
The prototype successfully connected the stages of signal acquisition, signal processing, programmed detection, and physical servo control into a single working system.
This project was developed as a proof-of-concept rather than as a clinically validated assistive device.

## Limitations
Several limitations were identified during development and testing:
* EEG signals are susceptible to electrical and environmental noise.
* Signal quality can vary depending on electrode placement and user movement.
* Eye blinks can introduce strong electrical signals that may interfere with other EEG activity.
* The prototype uses a relatively simple detection method rather than advanced machine-learning-based EEG classification.
* The prototype has not undergone clinical testing or validation.
These limitations would need to be addressed before a system based on this concept could be considered for real-world medical or assistive use.

## Future Improvements
* Implementing more advanced EEG signal-processing techniques.
* Improving filtering and noise reduction.
* Developing more reliable EEG classification methods.
* Increasing the number of distinguishable control signals.
* Improving the mechanical design and precision of the robotic arm.
* Reducing response time.
* Developing a more portable and compact system.
* Testing the system with a larger range of users and conditions.
* Exploring machine-learning approaches for more complex EEG-based control.

## Team & Contributions
This project was developed by a team of six members, with me serving as the team lead. I coordinated the project alongside contributing primarily to the programming and hardware integration.
My contributions included:
* Developing and refining the Arduino C++ code for EEG signal processing and robotic arm control
* Integrating and troubleshooting the EEG circuitry, Arduino, servo motors, and robotic arm
* Leading system testing and helping resolve hardware and software issues
* Coordinating the team's development and contributing to the overall project design and documentation
Other team members contributed to the mechanical assembly, testing, documentation, and other aspects of the project.


