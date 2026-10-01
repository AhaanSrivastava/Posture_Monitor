# Posture_Monitor
The posture monitor is intended to be a small wearble design that detects poor spinal posture and remind the user to stand/sit upright

Posture Monitor is a wearable posture-tracking device. It uses a tilt sensor (probably going to be an IMU sensor) to measure the orientation of the user's back.
When the device detects that the user has been slouching or has moved outside of their calibrated upright position, it activates a buzzer to remind them to correct their posture. 
My goal is to make a simple, affordable, and portable prototype that can provide immediate feedback without needing a phone or computer.

Currently according to the plan the device will consist of:

1.An IMU sensor to measure movement and orientation

2.A microcontroller to process the sensor data

3.A buzzer to provide an audio warning

4.A small battery to power the device

5.A wearable enclosure to hold the electronics

Also here are some ideas i would like to implement as i make it:
The user first calibrates the device while sitting or standing in an upright position. The microcontroller records this as the reference posture.
