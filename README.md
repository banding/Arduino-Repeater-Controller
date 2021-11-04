# Arduino Repeater Controller:
 Radio Repeater Controller
This is a basic repeater controller.
It has a Time out time, squelch tail timer and Ider timer.
The timer lengths can all be changed in the source code.
There is an Ider which runs at the end of the Id timer.
The Ider message is sent in CW and the message can be change 
using the Letter codes listed at the end of the source code.
There’s an audio control circuit suggestion, which you may find useful.
Additionally there should be some type of debounce added to the COS input of the Arduino.
Perhaps a cap and resistor to smooth out the COS transition. 
This interface will depend on the radio circuit being used.
