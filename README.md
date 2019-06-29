Hi 
Let me guide you through the project and the things used.

1)basic bot chassis with motors, motor driver, Arduino mega(coded with AVR language), 12v li-ion battery.

2)i2c protocol.

3)MPU6050.

4)Jumper Wires.

Some useful websites and links that you should read very very carefully before reading the code.
1)https://learn.sparkfun.com/tutorials/i2c/all
2)https://www.exploreembedded.com/wiki/Basics_of_I2C_with_AVR(whose library functions I used to make my project)
3)https://www.invensense.com/products/motion-tracking/6-axis/mpu-6500/(for the mpu6050 datasheet and register map)
Please read these thoroughly before coding 

I have used Arduino mega as a basic AVR board. Arduino boards can be programmed via AVR language by just including <AVR/io.h>.

The project doesn't require any external i2c library as the functions like start,read,write,stop are written as function in the AVR code itself.

Mpu6050 that is used is the project communicates with the AVR via i2c and has an address 0b1101000. 

The only changes that you would have to do to make yours work is the PWM and in1,2,3,4 pin as your board pins might vary.

Everything else is mentioned step by step in the code.
