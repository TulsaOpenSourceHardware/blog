Arduino Week 3
##############
:author: Patrick Foringer
:date: 2013-09-21 16:00

In an effort to prepare for out Arduino weather station project we sat down with the tmp36 temperature sensor this week to get a feel for its programming and hardware requirements.

Using our previous experience with a 2x16 char Arduino compatible LCD module we were able to output the current temperature coming off the sensor.

Interesting things learned about the Arduino this week:

* The converted integer range from analog in pins can vary between Arduinos or configuration.
* Use the aref pin to get a more accurate reading on reference voltages. This proved useful for retrieving a more accurate measurement from the tmp36.
* event if you wired something easily the first time, if you don't retain the documentation or links to your original resources you'll have a hard time the next time.

`Youtube Video <http://youtu.be/n4PPmYbIuXc>`_

`Github Source Code <http://git.io/eqEdEQ>`_
