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
