# Car_Simulator

Read guidelines below for assignment. This was a group assignment which consisted of one car moving, not multiple. No Raspberry Pis or socket programming used.

Note: The codes used in the following projects were taken from various sources and modified as instructed from professor.

UNC Charlotte Course: ECGR-4090

Special Topics in Electrical Engineering:

Internet of Things Professor: Dr. Arindam Mukerjee, PH.D.

Final Project: Internet of Things (IoT) Fall 2017

This project builds up on the Car Simulation App project. (See "Assignment 5: Android Car Simulator" below)

The user interface (car controls) remains on the Mobile Device.

The computation engine for simulating the Physics of the car should be implemented on the RPi.

The Mobile Device and the RPi for a single car should be connected by USB (WiFi may be too slow).

Each student in a group must have an Android mobile device and an RPi (together simulates a car). All the cars in a group will drive on the same track together.

Each student should be able to see ALL the cars from their group, and know their positions dynamically. 

Information about the mechanics for a particular car resides with the corresponding RPi, but all the RPis in the same WiFi network will have to communicate with each other and dynamically exchange information about their cars in REAL TIME. This information will be used by all the cars to know relevant details about the other cars.

Driving should be implemented in 2 modes:

City Driving Mode: where the RPi’s will exchange information with each other, and if needed, override the control signals from their respective drivers to ensure that the cars do not crash.

Racing Mode: where the control signals from the drivers override the safe autonomous driving if needed.

Deliverables:

Demo + Canvas Upload: .apk for car control and all files executing on RPi

Report: describing the code structure, descriptions of functions, optimizations, execution instructions, results, etc 

Due Date:
Nov 27-Dec 6

IoT – Fall 2017

Assignment 5: Android Car Simulator


GROUP Assignment: 

Implement an Android App for a Car Simulator using the GUI template below: (image not included)

There are 3 main layout parts:

1)	Top Left: a track with 2 lanes, on which the RED car moves in real time

2)	Top Right: a dynamic display of the main metrics we are interested in as the car moves 

3)	Bottom: controls for the driver to Start/Stop engine, Accelerate (increase engine RPM), Brake (with friction against the rotating wheels), and a Steering Wheel (showing the Steering Angle with respect to the front of the car always). The Steering Wheel could be controlled by Touch, Tap, or Drag.

The physics of the car movement and response is described in the following webpage:

http://www.asawicki.info/Mirror/Car%20Physics%20for%20Games/Car%20Physics%20for%20Games.html

Deliverables:

1)	Android App 

2)	Report file showing 

a.	all your formulas 

b.	all your assumptions

c.	individual contributions

Put the above in a directory with the name of your group, and upload the directory in Canvas. 

