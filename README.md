Stepper Motor Control with Arduino

This project controls a 28BYJ-48 stepper motor using an Arduino and a ULN2003 driver board.
The user enters a rotation angle (in degrees) through the Serial Monitor, and the motor rotates by that angle.
The code uses the Stepper.h library and converts degrees to steps using the formula:

steps = (angle / 360) * 2048


It demonstrates how serial input is aligned with motor step motion for precise angular control.
