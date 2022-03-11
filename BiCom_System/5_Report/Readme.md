# BiCom System

# About:

# Discription:

A Bicom system is the extention of the unidirectional RKE to bidirectional RKE. This systems shows alarm statuts, window status, car battery information and door status.Each of these functions are displayed with the help of LED. For window status blue switch on all led on at the same time. For alarm status blue switch pressed two times all led off at the same time. For battery switch press Three times all led in clockwise manner and for Door status press switch four times all led in anticlockwise direction

# Identifying Features:

* It will dislay the Window status of the car when Button is pressed once.
* It will display the alarm statusof the car when Button is pressed twice.
* It will display the battery status of car when the Button is pressed thrice.
* It will display the door status of car when the Button is pressed four times.

# High Level Requirements;

|ID|	Discription|
|---|---|
|HLR1|	System shall display Window status of the car|
|HLR2|	System shall display Alarm status of the car|
|HLR3|	System shall display Battery status of the car|
|HLR4|	System shall display Display status of the car|

# Low Level Requirements:

|ID|	Description|
|---|---|
|LLR1|	Press blue button once, All led ON at the same time.|
|LLR2|	Press blue button twice, All led OFF at the same time.|
|LLR3|	Press blue button thrice, All led glows in clockwise manner.|
|LLR4|	Press blue button four time, All led glows in anticlockwise manner.|


# test plan & Output:

# High Level Test Plan: 

|Test ID|	Description|	Input	Expected| Output|	Actual Output|
|---|---|---|---|---|
| 01 |	Print window status|	User presses button once|	Display window status of car	|Display window status of car|
| 02 |	Print alarm status|	User presses button twice|	Display alarm status of car	|Display alarm status of car|
| 03 |	Print car battery info|	User presses button thrice|	Display car battery info	|Display car battery info|
| 04 |	Print door status|	User presses button four times|	Display door status of car|	Display door status of car|

# Low Level Test Plan:

|Test ID|	Description|	Input	Expected| Output|	Actual Output|	Passed Or Failed|
|---|---|---|---|---|---|
|01	|check print window status|	User presses button once	|All LED's should on	|All LEDs should on	|Pass|
|02	|Check print alarm status|	User presses button twice	|All LED's should off	|All LEDs should off	|Pass|
|03	|Check print car battery info|	User presses button three times	|LED's should on once clockwise manner	|LED's should on once clockwise	|Pass|
|04	|check print door status	|User presses button four times	|LED's should on once anticlockwise manner	|LED's should on once anticlockwise	|Pass|

# State of art:

* Buttons shall be provided to ease the access of available features.
* Window status of the car is displayed with a button press.
* Alarm status of the car is displayed with a button press.
* Battery status of the car is displayed with a button press.
* Display status of the car is displayed with a button press.

# Behavioural Flowchart:


![Behavioural flowchart](https://user-images.githubusercontent.com/98880912/157857548-af2e3bfa-8c21-42f9-8205-9f79110d9ea5.png)

# Structural Flowchart :


![Structural Flowchart](https://user-images.githubusercontent.com/98880912/157857552-c5c955a1-6b4e-4bfa-9938-a70682dcc744.png)


# SWOT Analysis:

![images](https://user-images.githubusercontent.com/98880912/157847938-a582fbca-bfa5-464a-a5c9-cf117a5443fd.jpg)


# Strength:

* we can check our window,alarm,battery and door status with button click.
* No need of human interaction needed.

# Weakness:

* It has limited range and Replacing a lost fob costs much more than a traditional key.
* Security is not that poweful.

# Opportunities:

* Allow users to use their smartphones for checking the security factor of car and even controlling extra features.
* Wide exposure in automobile industry as it's cost efficient also.

# Threats: 

* Thieves, however, are rising to the challenge, using radio transmitters to perform ‘relay’ car hacks to capture the signal from the car’s fob possibility for hackers to manipulate the technology and steal your vehicle
* User has to wait till the first task is completed to give another command.


# 5W's And 1H:

# Who

* People who are having own car.

# What

* The system can control the feature of car by wireless key.

* The status of different features of the car is given by LED's or display.

#When

* When the user wants to know the status of windows , alarm ,battery and door.

# Where

* Where the owner want to use the features of ther car provided .

# Why

* To know the working and status of different features of the car.
* To use different feature of the car with ease .
* To ensure the comfortness.

# How

* The features can be used by buttons of your remote or device in a single click .

# Goals of this project :

- **_To reduce the human effort_**
- **_To provide quicker & better Display technique_**

