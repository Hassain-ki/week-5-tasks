# week-5-tasks

task 1: build a circuit that recives input of 12v-35v, and outputs three diffrent levels of voltage 5v,9v,12v
I managed to build a 35v voltage regulator circuit that outputs 5v. I used LM7805 IC. 


task 2: build a circuit to control the switching of the power of servo motor
Arduino and transistors are used to control the motion of servo motors.
Arduino controls the dgree of motion of the motors and the siwtching of transistors to power the motors.
The code is built to show the accurecy of motion of motors , and the ability to switch off the motors to not loss power.
the code turns on the transistor to power the motor, then sends a signal to the motor to move to the determined angle. afterthat, turns the transistor off.
lastly, the code tries to send a signal to the motors while the transistors are off. the result is that the motors are not moving.
