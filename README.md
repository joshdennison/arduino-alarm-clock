# arduino-alarm-clock
Required components- 

arduino uno

1x piezo buzzer

1x 16x2 lcd display

1x resistor 5k1 ohm

1x resistor 220 ohm

3x push buttons

jumper cables

1x breadboard

This is code for an alarm clock that uses and arduino uno. This project has 3 buttons, one which is used to enter the set time mode, one to increment the hours and one to increment the minutes.
set up 3 buttons, next to each other, the left one is connected to pin 4, middle one connected to pin 5 and right one connected to pin6 each using a 220 ohm pulldown resistor connected to GND
hook up a piezo buzzer to pin number 5.

hook up the following parts of the lcd to the given pins - rs = 9, e=10, d4=11, d5=12, d6=13,d7=8

This has a 3 button interface, allowing you to set the alarm, pressing the left button after setting the alarm will allow you to start the clock, with the middle button incrementing the hours, and the right one incrementing minutes.

wire A on the LCD to 5v+ and K on the LCD to Gnd 

connect VSS to GND and VDD to GND

connect V0 to ground with a 5k1 ohm resistor
