# Futuristic-Mouse
Arduino based control of laptop with the help of Python3.
We will use our hand gestures to control certain functions of a computer like play/pause a video, move left/right in a photo slide show, scroll up/down in a web page and many more.

Principle behind the Project:-

The principle behind the Arduino based Hand Gesture Control of Computer is actually very simple. All you have to do is use two Ultrasonic Sensors with Arduino, place your hand in front of the Ultrasonic Sensor and calculate the distance between the hand and the sensor. Using this information, relevant actions in the computer can be performed.

Components Required:-

Arduino UNO x 1                                         
Ultrasonic Sensors x 2  
USB Cable (for Arduino)                                       
Few Connecting Wires  
A Laptop with internet connection 

Design of the Project:-

The design of the circuit is very simple, but the setup of the components is very important. The Trigger and Echo Pins of the first Ultrasonic Sensor (that is placed on the left of the screen) are connected to Pins 11 and 10 of the Arduino. For the second Ultrasonic Sensor, the Trigger and Echo Pins are connected to Pins 6 and 5 of the Arduino.

The following are the 5 different hand gestures or actions that I’ve programmed for demonstration purpose.

Gesture 1: Place your hand in front of the Right Ultrasonic Sensor at a distance (between 15CM to 35CM) for a small duration and move your hand away from the sensor. This gesture will Scroll Down the Web Page or Decrease the Volume.

Gesture 2: Place your hand in front of the Right Ultrasonic Sensor at a distance (between 15CM to 35CM) for a small duration and move your hand towards the sensor. This gesture will Scroll up the Web Page or Increase the Volume.

Gesture 3: Swipe your hand in front of the Right Ultrasonic Sensor. This gesture will move to the Next Tab.

Gesture 4: Swipe your hand in front of the Left Ultrasonic Sensor. This gesture will move to the Previous Tab or Play/Pause the Video.

Gesture 5: Swipe your hand across both the sensors (Left Sensor first). This action will Switch between Tasks.

Fot this project, you need to install latest version of Python. After installing Python, you need to install some libraries in python using command prompt.
the libraries are:
serial library :- command for CMD : 'python -m pip install serial'  
Pyautogui library:- command for CMD: 'python -m pip install pyautogui' or 'pip install pyautogui'






CREDITS:- Raviteja                          
Website :- https://www.electronicshub.org/arduino-based-hand-gesture-control-computer/
