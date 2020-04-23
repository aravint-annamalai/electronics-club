# MINI TASK - 1

## 1. KEYBOARD USING SMD SENSORS:

Link: https://www.instructables.com/id/Velocity-Sensitive-Cardboard-Keyboard/

In this project, a small keyboard is made using cardboard. The cardboard is cut into various small pieces which corresponds to various keys in the keyboard. The various pieces are joined using hot silicone. There are 5 keys which correspond to C,D,E,F,G frequencies and is fitted into a larger cardboard using rubber straps, and there are slots made for inserting them onto the base. SMD sensors are used to detect which key is being pressed, and is therefore fitted below each key of the keyboard. The sensors are connected to 5 analog pins of an Ardunio Mega and is coded using the toneAC library such that sound of the corresponding frequency comes when that particular key is pressed. In this way, this project was implemented.

## 2. AUTOMATIC WATER LEVEL CONTROLLER:

Link: https://www.electronicshub.org/water-level-controller-using-8051-microcontroller/

In this project, the level of the water is automatically controlled using the 8051 microcontroller which is programmed using the Keil uVision IDE. The aim of this project is to control the water in the tank such that the motor stops running automatically when the tank is full and it starts running when the tank is empty. This reduces human intervention as well as water losses due to water overflowing from the tank. This is based on the principle that water conducts electricity. Wires are connected to different levels of water - either LOW, MEDIUM, HIGH or QUARTER full, HALF full,... There is an LCD display as well which denotes the level of water present in the tank, just in case if someone wants to know the level of water. If initially the tank is empty, the motor starts running, and when the water at appropriate levels are reached, the LCD displays the appropriate level of water. When the tank is full, the motor is automatically switched off. When the water tank is on the EMPTY level, the motor gets turned on automatically, to refill the water in the tank. The display on the LED and the control of the motor is controlled by the 8051 microcontroller.
