# Getting Started with K8

A guide on how to get up and running quickly with the K8 robot from [Insksmith](www.inksmith.ca/pages/k8-robotics-kit) (www.inksmith.ca/pages/k8-robotics-kit)

## What is K8?

K8 is a two-wheeled programmable robot powered by the micro:bit. The electronic components within K8 are easy to use and designed for beginners.

## What is inside K8?

* 2 x DC motors
* 1 x Line follower made up of 3 infrared sensors
* 1 x ultrasonic sensor (used for object detection)
* 2 x Servo motors

## Programming K8

To program K8 we first need to open the [MakeCode editor](www.makecode.microbit.org) (www.makecode.microbit.org) into your chosen web browser. Click on a new project, within the programming menu click on Advanced. Scroll to the bottom and click on Extensions, within the search bar at the top type K8 and click on the image of "K8".
![K8 Extension](/Images/Extension.png)

## Controlling The Motors

Now that we have got up and running with MakeCode we can start programming!

1. Click on Input, click and drag an on button A pressed to the coding area and drop it.
2. Click on motion, click and drag drive straight speed 0 to the coding area and attach it within on button A pressed.
3. Click on 0 and type 50.
![Driving straight code](/Images/DrivingStraight.png)
4. Click on Download to download the code file to the micro:bit. Once the light on the back of the micro:bit has stopped blinking unplug the micro:bit from the computer and attach it to K8.
![K8 Robot](/Images/K8.png)  

Turn the battery pack and controller board on, put K8 on the floor and press button A on the micro:bit. K8 should now start driving forward.

Let's see what else K8 can do.

Modify your code to look like this:
![Driving Test](/Images/DrivingTest.png)

## Line Following

The infrared sensors point downwards and detect light and dark surfaces.

To make our track we will want to use black electrical tape on a white surface and make sure it is a closed-loop. ![Track](/Images/Track.png)

### Configuring The Light Sensors

1. Turn K8 upside down so the sensors are pointing upwards.
![Line seonsors](/Images/LineSensor.png)
2. Turn the dial clockwise until the red signal light on the IR (infrared) sensor turns on.
3. Very gently turn the dial counter-clockwise until the red light turns back off, this makes sure the sensitivity of the sensor is maximised and the sensor can tell the difference between black and white.
[How to Calibrate IR sensors](https://vimeo.com/373893397) (https://vimeo.com/373893397)
4. Repeat for the steps above for the other two sensors.
5. Create the following program to test the sensors.
![Testing IR seonsor](/Images/TestingIR.png)

 Download the code to the micro:bit, once the light on the back of the micro:bit has stopped blinking unplug the micro:bit from the computer and connect it onto K8.
6. Place K8 on a white surface, if the sensors are calibrated correctly the first, third and fifth column of LEDs on the micro:bit should light up.
![IR Sensor configured](/Images/IRSensorConfig.png)
7. If this doesn't work repeat steps one and two.
8. Place a bit of black electrical tape on the white surface and slowly sweep K8 over the line. The columns of LEDs should turn off when the corresponding sensor sees the black tape.

### Testing The Track

1. Create a closed-loop track using black electrical tape on a white surface.
2. Create the following code to test your track.
![Line following code](/Images/LineFollowing.png)

## Object Detection

K8's eyes may look similar to ours with being two round holes, but they behave very differently. K8's eyes behave more like the way a bat or dolphin would detect objects within their habitat using echolocation. Echolocation is where properties of sound are used to bounce signals off of objects and judge how far away the objects are.

Copy the code below to test K8's sonar and make sure it is detecting objects correctly.
![Testing the sonar sensor](/Images/TestingSonar.png)

Place K8 in front of a wall, move K8 closer to the wall and further away from the wall. The LEDs on the micro:bit should be changing, this shows that the sonar sensor is working and K8 is detecting objects.

Here is some sample code to show K8 detecting and avoiding objects.
![Driving with Sonar code](/Images/DrivingSonar.png)

## Using The Radio

We are going to use the radio function on the micro:bits so we can introduce a second micro:bit to control K8.

Here is the example code for the controller:
![micro:bit controller code](/Images/Controller.png)
Here is the example code for K8:
![K8 Code](/Images/K8Remote.png)

## Conclusion

We have covered the basics of programming K8. You can now go and explore with K8 and MakeCode to see what else K8 can do!