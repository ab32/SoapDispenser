# SoapDispenser

A motion sensor soap dispenser built using ***Arduino nano***, ***Ultrasonic Sensor HC-SR04*** and a ***servo***

![Capture](https://user-images.githubusercontent.com/44835095/162645326-06d1beb2-eee9-4028-93fa-d17fe22ea29c.PNG)

# Description

I will be going through the process step by step so that you as the reader can follow along. I got motivated by a classmate to start doing projects. This is my first ever project uploaded anywhere on the internet so be kind. **First of I need to insert a caution, that you as a reader use the right type of servo, because I didn't do it. It was a design flaw. I used a 9g servo, it is a very tiny one and doesn't output enough force to pull down the soap dispenser. Anything stronger than the 9g servo will do the job.**

This project is very easy executable and even people whom are new to programming can follow along. You just have to connect everything right with the ultrasonic sensor, arduino nano and the servo then the code will do the rest. You can even change the angle of which the servo will move.

# Getting started

The component needed for this project are very basic and you might have access to it. 

The components for the soap dispenser are:
* **Servo**
* **Ultrasonic Sensor HC-SR04**
* **Arduino nano**
* **Breadboard**(Optional)
* **9V battery**

Follow these steps to get it working, first of you need to follow the schematics down below to get everything to work properly. 
![arduino uno motion detector](https://user-images.githubusercontent.com/44835095/163576349-197563ae-33a7-4417-953b-27b4978afc52.PNG)

Once you've connected every output and input it should be working. If the ardunio nano is missing a power source it will not work. Either have it connected to your computer via USB or use a **9V** power source and connect with pin **Vin**.

Next off you download getInfoFromArduino.cpp file from the repository. 
