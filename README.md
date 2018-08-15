# CSE461
The repositroy contains the code for a simple dust responsive proximity aware water sprinkler.

A demo video of the project can be found [here](https://youtu.be/iyoZcHU2n-o?t=1m20s).

Components used:
1.	Arduino Uno R3
2.	Optical dust sensor (GP2Y1010AU0F)
3.	2 sonar sensors (HC-SR04)
4.	Signal buzzer
5.	Mini water pump
6.	I2C LCD display (16x2)
7.	Lead acid battery
8.	1 channel 5V relay

While there are two sonars listed only has been used. Because either the other one was never properly connected to begin with or it somehow got disconnected while the project was being moved around. Debugging it would mean, opening up the entire project which has been glued using hot glue. 

The required LCD library can be found [here](https://bitbucket.org/fmalpartida/new-liquidcrystal/downloads/). Version 1.3.5 has been used for the project
