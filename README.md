# BMP280-STM32duino Library

This library uses I2C communication with STM32 and read the Temperature( degC) , Pressure (mBar) and Altitude (m).


Pin Connection : 
===============

BMP280-----STM32

VDD   ----> 3.3V

GND   ----> GND

SDA   ----> PB7

SCL   ----> PB6

SDO   ----> GND   (slave address 0x76)

CS    ----> VDD   (HIGH for I2C)


Instructions :
=============

Copy the BMP280 folder to Arduino/libraries

Restart Arduino and Upload "measurments" sketch in Arduino.
