# amradiodisplay
For ELEC 391 Project 1; using an Arduino Uno in conjunction with a designed from scratch AM radio to display volume and AM frequency channel. 

The volume bar is an LED display reading the voltage difference in the potentiometer and lights the LEDs based on the volume/voltage difference.

The frequency is read using pin 5 of the Arduino and by utilizing the FreqCount library. It is then displayed on a 7 segment display. 
