# LINE-FOLLOWER
PCB DESIGN OF LINE FOLLOWER USING EasyEda

https://oshwlab.com/rochelle1511/linefollowerbot


![image](https://github.com/user-attachments/assets/4f3fd23a-b241-4afc-8adc-71b579526690)

# Line Follower Robot using PID Control

This is a simple line follower robot built using an Arduino and an 8-channel QTR sensor array. It uses a PID (Proportional, Integral, Derivative) control algorithm to follow a black line on a white surface accurately and smoothly.
The robot reads the line position using the QTR sensors and adjusts the motor speed based on how far off the center it is. The PID values can be tuned to improve performance depending on how sharp the turns are or how fast the bot needs to go.

# How It Works:
The QTR sensors detect the position of the black line and return a value between 0–7000 (based on 8 sensors).
The robot calculates the error from the center (3500), then uses that to adjust motor speeds using PID.
Motors are controlled using PWM through a motor driver (L298N or similar).
There’s a calibration mode activated by a button before starting to make sure the sensors work properly on different lighting/surface conditions.
A second button is used to start/stop the bot.

# Hardware Used:
1.Arduino Uno
2.8x QTR Reflectance Sensors
3.L298N Motor Driver
4.2 DC Motors
5.Push buttons (for calibrate and start)
6.Battery or USB power



