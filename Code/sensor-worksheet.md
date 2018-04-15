# Sensor Worksheet

## Touch Sensor

The analog EV3 Touch Sensor is a simple but exceptionally
precise tool that detects when its front button is pressed or released and can count single and multiple presses. 

* The touch sensor only ever outputs one of two values: true or false. 
* The touch sensor is commonly used for programming “move until touch sensor is pressed/released/bumped” or start or stop when a touch sensor is pressed.

![touch-sensor-block](/resources/touch-sensor-block.png)

**What are the three possible states that the touch sensor can be in?**

1.     

2.     

3.     

**Assuming your motor is attached to ports B + C, and you have a touch sensor attached to port 1, describe what the robot will do while running this program:**

![touch-sensor-sample-code](/resources/touch-sensor-sample-code.png)

Hint: The green blocks are both Move Tank blocks, the first orange block is a Start Block, and the second orange block is  a Wait Block.

## Ultrasonic Sensor

The EV3 Ultrasonic Sensor generates sound waves and reads their echoes to detect and measure distance from objects. It can also send single sound waves to work as sonar or listen for a sound wave that triggers the start of a program. 

![ultrasonic-sensor](/resources/ultrasonic-sensor.png)

* Measures distances between one and 250 cm (one to 100 in.). Will show a value outside of this range if the sensor is too close or too far from the object to read the distance.
* Accurate to 1 cm or 0.3 inches
* Eyes light up to indicate which mode the sensor is operating in. The illumination is constant while the sensor is emitting and blinks while listening.

**What are two different reasons that the ultrasonic sensor would read a value of 255cm?**

1.     

2.     

**True/ False: The ultrasonic sensor will have a more accurate reading when it islined up with the center of an object.**

 

**Assuming your motor is attached to ports B + C, and you have an ultrasonic sensor attached to port 4, describe what the robot will do while running this program:**

![ultrasonic-sensor-sample-code](/resources/ultrasonic-sensor-sample-code.png)

Hint: The green blocks are both Move Tank blocks, the first orange block is a Start Block, and the second orange block is a Wait Block.

## Color Sensor

The EV3 Color Sensor distinguishes between eight different colors. It also serves as a light sensor by detecting light intensities. 

* Senses the brightness of light and converts it to a number between 0 (darkest) and 100 (brightest).
* Our eyes adjust to conditions automatically but for EV3 sensors we must do this manually - this is called **calibration**.

The sensor can be programmed to use three different light modes:

1. Ambient Light: Sensing the light out in the world (room).
2. Reflected Light: Emitting light out of its LED and picking up on what comes back. Best to use for big changes is light intensity, such as the difference between black and white. 
3. Color: Can emit red, blue, and green, and sequence through colors at very high rates. The sensor measures the light that comes back and decides what color it’s seeing. 

The sensor reading is an **average** of the brightest of the entire area it can “see”. 

* Mount the sensor on the robot so it's close to the surface on which the wheels roll
* If you use the "generate light" option, you can see the area the sensor will "see" when you place the robot on a surface

What are the three different modes the color sensor can be in?





Which mode is best for determining whether the lights in a room are  on or off?

 



Which mode would you use to determine whether the sensor is detecting black or white?



![color-sensor-black-and-white](/resources/color-sensor-black-and-white.png)