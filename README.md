# pick-and-painting-station-RAPID
This project was developed in RAPID and the simulation environment of RobotStudio (ABB). 

## 🎯 Goal
The goal of this project was to implement a station that included two conveyors and an industrial robot (in this case IRB2600). The focus was to program safe trayectories, handle the I/O signals and implement smart components such as the gripper and the aerosol tool. The velocities, placements, procedures and security may not be the industry optimal as the focus was to learn about programming and exploit functionalities in RobotStudio.

## ⚙️ Procedure of the Station
First, the already assembled product is transported by the first conveyor. A line sensor at its end stops the movement when an object is detected and activates the pick-up. The robot starts with the smart gripper attached and moves to the object's position. After arriving, the (short) line sensor implemented in the gripper detects the object, commanding the tool to close. After that, the robot places the object on the table, moves to a secure position, deattaches the gripper and attaches the new aerosol tool. Then, the robot proceeds to paint the product and, again, changes to the gripper tool to finally place the resulting object in the second conveyor. 

## ▶️ Simulation
Youtube Link: https://youtu.be/DVk3db-Uiew






