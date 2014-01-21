fingerprint_gt511c3
===================

Arduino script for working with the GT-511C3 fingerprint scanner

https://www.sparkfun.com/products/11792

I had some issues getting things working with the code from http://wordpress.hawleyhosting.com/ramblings/?p=375

Using the wiring they have described and snippets from their library, I managed to include all the methods that I needed within an Arduino library without the need for any other libraries and things have been working well for me since I got that going.

This uses the Arduino Mega with the connection to Serial 2 rx/tx

FPS connections:

digital pin 17 (arduino rx 2, fps tx)

digital pin 16 (arduino tx 2 - 560ohm resistor - fps tx - 1000ohm resistor - ground)

* look at serial output for some helper commands
* sometimes the commands need a character in front of them (any character) because i didn't need to debug this
