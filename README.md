# rgbled

## description
 rgbled is a python script for controlling rgb leds using gpio on rpi4/5 single board computers.

## usage
 _rgbled <color 1> <time 1> ... <color n> <time n>_

 colors are integers 0 - 0xffffff 3 * 0-0xff controlling red green blue 0xff0000 is red & 0xff is blue.
 times are in seconds ie 0.5 or 2
