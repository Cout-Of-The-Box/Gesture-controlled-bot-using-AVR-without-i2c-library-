# Gesture-controlled-bot-using-AVR-without-i2c-library-
Hi 
Let me guide you through the project 
Things used 
1) basic bot chassis with motors, motor driver, Arduino mega(coded with AVR language), 12v li-ion battery.
2) i2c protocol 
3) MPU6050 
4) Jumper Wires 

I have used Arduino mega as a basic AVR board.
Arduino boards can be programmed via AVR language by just including <AVR/io.h>

The project doesn't require to include any external i2c library as the functions like start,read,write are written as function in the AVR code itself

