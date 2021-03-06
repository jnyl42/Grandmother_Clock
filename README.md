# Grandmother_Clock by Jason Nyland

A minimalistic LCD clock that only shows the day of week

Grandmother Clock is a program that displays the weekday 
in word form (eg "Tuesday") on a bright, uncluttered
LCD display so that my grandmother can see what day it is
while taking her pills.  It's a clean, simple clock for 
the forgetful!  Many clocks show the weekday, but they are
optimized for battery life with dim LCDs, and are cluttered 
with extra information.

You will need:
- Arduino
- 16x2 LCD module
- DS3231 RTC module

Notes:
If you don't use the OSEPP LCD shield, you may need to 
reconfigure LCD pinouts as appropriate.

Features to add:
- RTC support for DS3231 module (done)
  - RTC module interrupt to save battery
- Motion-activated backlight with PIR sensor
  - Investigate battery power once backlight can turn off

Here is a prototype in a makeshift cardboard enclosure:
<br>
<a href="http://imgbox.com/DAsC2JMJ"><img src="https://4-t.imgbox.com/DAsC2JMJ.jpg"></a>
<br>
(click for big)