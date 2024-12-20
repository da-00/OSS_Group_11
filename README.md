# Self-Stablilzing Platform
In unstable environments with vibration or uneven terrain, sensitive equipment like cameras, drones, and robotic systems require stabilization to maintain precision and prevent damage.
A self-stabilizing platform solves this by detecting motion through sensors and automatically correcting it using servo motors.

![image](https://github.com/user-attachments/assets/9217e74b-f932-431d-b3a8-4e4d283c71e0)
![image](https://github.com/user-attachments/assets/122dbfb1-b78f-46ec-8873-8febcf9004ad) 

# Key Features
Gyroscope Sensor: Measures real-time motion (pitch, yaw, roll).
Arduino: Processes sensor data to calculate adjustments.
Servo Motors: Execute precise physical corrections based on commands.

# Structural Design
The platform features three independent axes converging at a single point for full rotational freedom. 
Servo motors are positioned near these axes with L-shaped connectors, ensuring smooth, non-interfering adjustments.
![image](https://github.com/user-attachments/assets/7d021f35-ea7f-49d8-8842-4381419619b1)


# About the Code
This Python-based implementation integrates sensors, microcontrollers, and servo motors to detect and correct motion. 
It ensures high precision by stabilizing all three axes (pitch, yaw, roll) in real time, making it ideal for dynamic applications like drones, logistics, and VR systems.

# Reference
https://howtomechatronics.com/projects/diy-arduino-gimbal-self-stabilizing-platform/
https://www.electromaker.io/project/view/arduino-based-self-stabilising-platform?srsltid=AfmBOopZrDM_UEU7sFXzwSELbgBO2YVgjZWLpByfEMUdhdk7BIFOzg0P
https://ieeexplore.ieee.org/document/6843648
