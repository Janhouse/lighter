Lighter
=======

Script to automatically control Macbook Air (2012) screen and keyboard backlight brightness using data from the built in light sensor.

Dependencies: notify-send, Macbook Air (applesmc module), Perl modules listed in the lighter.pl


Usage
=======

Run it (probably as root).

Create file that contains word "locked" in /tmp/.apple_sensor.txt to temporarily disable automatic changing of backlight.
(I would suggest a menu entry that creates/removes that file.)
