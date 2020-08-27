# AC Fan Speed Control using Arduino and TRIAC
 
- It is easy to turn on or off any home appliance by using a switch or by using some control mechanism as we did in many Arduino based Home Automation projects. But there are a lot of applications where we need to control the AC power partially, for example, to control the speed of the Fan or the intensity of a Lamp. In this case, the PWM technique is used, so here we will learn how to use Arduino generated PWM to control AC fan speed with Arduino.

- In this project, we will demonstrate Arduino AC fan speed control using TRIAC. Here phase controlling method of the AC signal is used to control the AC fan speed, using PWM signals generated by Arduino. In previous tutorial, we controlled the DC fan speed using PWM.

- Components Required
- Arduino UNO
- 4N25 (Zero crossing detector)
- 10k Potentiometer
- MOC3021 0pto-coupler
- (0-9)V, 500 mA Stepdown Transformer
- BT136 TRIAC
- 230 VAC Axial AC fan
- Connecting wires
- Resistors
- Working of AC fan control using Arduino
The working can be divided into four different parts. They are as follows

1. Zero-Crossing Detector
2. Phase Angle Controlling circuit
3. Potentiometer to control the Fan speed amount
4. PWM signal Generation circuit
