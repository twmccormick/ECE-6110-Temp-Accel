# ECE-6110-Temp-Accel

This code is mainly a demo for reading sensor values over I2C and then displaying them
over UART on the B-L475E-IOT01A1 development board.

Essentially, this project reads data from the on-board temperature sensor as well as the 
on-board accelerometer sensor and then sends the data over UART (8n1 9600 baud). In
addition, as only a single sensor's data is sent, pressing the blue button on the board triggers an interupt 
that toggles whatver data is sent over.

Initially, the temperature data is displayed, and if the button is pressed, then the accelerometer data is displayed.
This change is infinitely-toggleable. 
