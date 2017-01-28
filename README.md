# NavPi
I'm designing a Navigation Server using a Raspberry Pi3 to collect data from sensors and radio messaging systems, sending this data to be used on either a PC or Mac running OpenCPN.

Current list of components:

Raspbery Pi 3
NooElec mini SDR/DVB-T (used for an AIS receiver)
  > looking at other options to also build a receiver for Navtex   
BU-353S4 GPS (Looking at getting a Adafruit Ultimate GPS to future imbed)
Adafruit 9-DOF Absolute Orientation IMU Fusion Breakout - BNO055 (using as a gyro/mag/ROT compass)
  > Driving this compass, I plan to use a Ardunio Pro Mini or something similar) sending NMEA data 
    to the server
SN65HVD230 CAN board to connect to a NMEA 2000 network
I should be able to connect to NMEA 0183 diectly to Raspi?

*** Note ***
I’m not a programmer, although, I am trying to learn. I could use some help to successfully
implement all the programing needed to get this project working.

In addition, I don't know how to build GUI programs to make data boxes where it can readout the  
data sent from the server on the PC or Mac. I assume this is Java?

