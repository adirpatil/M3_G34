
# High level test plan:

|Test ID|	Description|	Input|	Expected output|	Actual output|
|---|---|---|---|---|
|01|	Lock	|User presses button once|	Lock the car|	Lock the car|
|02|	Unlock|	User presses button twice|	Unlock the car|	Unlock the car|
|03|	Alarm Activate/Deactivate|	User presses button three times|	Activate or Deactivate alarm|	Activate or Deactivate alarm|
|04|	Approach light|	User presses button four times	|Turn on approach light|	Turn on approach light|

# Low Level Test Plan:

# Low level test plan:

|Test ID|	Description|	Input|	Expected output	|Actual output|	Passed Or Failed|
|---|---|---|---|---|---|
|01|	check for lock|	User presses button once|	All LEDs should on|	All LEDs on| 	Pass|
|02|  Check for unlock|	User presses button twice|	All LEDs should off|	All LEDs off|	Pass|
|03|  Check for alarm activate/deactivate|	User presses button thrice|	LEDs should on in clockwise direction|	LEDs on in clockwisedirection| Pass|
|04|	Check for approach light|	User presses button four times|	LEDs should on in anticlockwise direction|	LEDs  on in  anticlockwiseDirection|	Pass|
