# Move a DC Motor with H-Bridge
## Task Description:- 
Run H-bridge with a DC motor using Arduino on Tinkercad
#### 
### Program:
Tinkercad
#### 
### Duration:
1 hr and 30 minutes (approximately)
#### 
## Part 1 - Move the DC Motor Clockwise and Counterclockwise 
#### 
## A Step-By-Step Guide:-
1- Open [Tinkercad](https://www.tinkercad.com/) and click on create, then click on circuits.
#### 
### 2- Gather the components, which are:
#### 
- Arduino Uno R3
- L293D H-Bridge Motor Driver (place it on the breadboard)
- 2 Pushbuttons (place both of them on the breadboard next to the H-Bridge)
- DC Motor
- Breadboard
#### 
### 3- Make the Necessary Connections:-
#### 
#### - Arduino Connections:
1- Connect it to the Breadboard
2- Connect it to the L293D H-Bridge Motor Driver
#### 
#### - H-Bridge Connections:
1- Connect it to the DC Motor
2- Connect it to the Breadboard
####
#### For a clear understanding of the wiring and connections, follow this circuit diagram:
#### 
![‏‏لقطة الشاشة (2202)](https://github.com/user-attachments/assets/63b9e69f-3acb-42b4-bec7-15393f7af54b)
####
4- Write the Code
#### 
### Link:
[Arduino and H-Bridge Controlling DC Motor (clock/anti-clock)](https://www.tinkercad.com/things/ekcbrObkjsZ-arduino-and-h-bridge-controlling-dc-motor-clockanti-clock)
#### 
## Part 2 - Use and program 2 DC Motors so that they move forward and backward, and then turn to the right and left (Robot Movement)
#### 
## A Step-By-Step Guide:-
1- Open [Tinkercad](https://www.tinkercad.com/) and click on create, then click on circuits.
#### 
### 2- Gather the components:
#### 
- Arduino Uno R3
- L293D H-Bridge Motor Driver (place it on the breadboard)
- 2 Slideswitches (place both of them on the breadboard next to the H-Bridge)
- 2 DC Motors
- Breadboard
#### 
### 3- Make the Necessary Connections:-
#### 
#### - Arduino Connections:
1- Connect it to the Breadboard
####
#### - DC Motors' Connections:
1- Connect them to the Breadboard
#### 
#### For a clear understanding of the wiring and connections, follow this circuit diagram:
#### 
![‏‏لقطة الشاشة (2201)](https://github.com/user-attachments/assets/2997bab6-faad-4bbb-b4ee-ea1cc55a0806)
####
4- Write the Code
#### 
### Process of Thought:
For the 2 Slideswitches, we will pretend that they’re “Bump Sensors” mounted on the front of the robot. As a result of this way of thinking, it’s natural to say that if one sensor bumps into something, then we want the robot to turn either to the left or to the right, and if both sensors bump into something then we want the robot to go in reverse, or walk backward, sort of like an “Obstacle-Avoiding-Algorithm”. When running the code for this circuit, you’ll see that the “rpm” on both the DC Motors is a positive number, but when you toggle one of the Slideswitches, its corresponding DC Motor will start moving in reverse direction. Now, if this was a real robot with left and right DC Motors driving around, you can imagine how that would cause the robot to either turn left or right, or even go forward or drive in reverse depending on the combination of what the 2 motors are doing.
#### 
### Link:
[H-Bridge Controlling 2 DC Motors (left/right - forward/backward)](https://www.tinkercad.com/things/01jYXr3Pisy-h-bridge-controlling-2-dc-motors-leftright-forwardbackward)
#### 
