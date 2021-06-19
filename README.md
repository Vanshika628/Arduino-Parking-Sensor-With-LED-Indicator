# Arduino-Parking-Sensor-With-LED-Indicator


#### Hi, Vanshika this side, I am here to give a bit of description about the project that i made. 

👇                                                                                                                                      


![Diagram](https://user-images.githubusercontent.com/79529647/119790780-0cd4c600-be89-11eb-9bc9-00fc480c5582.jpg)

#### #As you could see in this image the Arduino UNO is connected to the Ultrasonic Sensor as well as Bread Board.
#### #Arduino's Digital pins are connected to the Bread board(LED's as well as resistors).
#### #Arduino's GND is connected to the Breadboard .
#### #Arduino's power pin and GND is Connected to the VCC and GND of the Ultrasonic sensor.
#### #Ultrasonic's trig and echo is connected to the digital pins of the Arduino board.
#### #The Arduino board is connected to the laptop's port through usb to provide it supply.
##### #For the clear pic of the diagram: https://github.com/Vanshika628/Arduino-Parking-Sensor-With-LED-Indicator/blob/main/Diagram.jpg
                                                                                                                          
👆    

### What is the purpose of an Ultrasonic sensor?
#### --An ultrasonic sensor is an electronic device that measures the distance of a target object by emitting ultrasonic sound waves, and converts the reflected sound into an electrical signal.

### What is trigger and echo in ultrasonic sensor?
#### --The Trigger and the Echo pins are both I/O pins and hence they can be connected to I/O pins of the microcontroller(Arduino). Once the wave is returned after it getting reflected by any object the Echo pin goes high for a particular amount of time which will be equal to the time taken for the wave to return back to the sensor.


### Explain Arduino uno? 
#### -The Arduino Uno is an open-source microcontroller board based on the Microchip ATmega328P microcontroller and developed by Arduino.cc. ... The board has 14 digital I/O pins (six capable of PWM output), 6 analog I/O pins, and is programmable with the Arduino IDE (Integrated Development Environment), via a type B USB cable.

![Introduction-to-Arduino-UNO (3)](https://user-images.githubusercontent.com/79529647/119869684-6236c480-bed5-11eb-8891-4a6393d527bb.jpg)



## Observation:
#### The object which is in front of Ultrasonic sensor, as it moves down the LED's starts glowing as per the decreasing distance. 

#### Here is the link of the video:https://github.com/shubh0811/LED-DISTANCE-INDICATOR/blob/master/Project%20video.mp4

## Explanation:
#### The ultrasonic sensor catches the object as it comes in its range(range decided in the code). So before the starting of the project , the code is to be written(on IDE) and uploaded in the Arduino Board. Link for the code:https://github.com/Vanshika628/Arduino-Parking-Sensor-With-LED-Indicator/blob/main/Code%20for%20the%20Project.txt
#### Now as per the code i have written that when the object is at 25cm away from the sensor, glow the 7th LED . Than as the distance decreases the another LED's starts glowing as per the code. In the code I also mentioned about all the input and the output pins for the Bread board and Ultrasonic sensor.
#### Now this looks bit easier because all the work is done by a simple code. 


## Board used:
#### #Arduino UNO

## COMPONENTS USED:
#### 1) LED -7
#### 2) Resistor - 7(220 ohm)
#### 3) Ultrasonic sensor
#### 4) Bread Board


Took help from youtube videos!                              





