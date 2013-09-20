ITP-Gloves
==========

This is an assembly of The Gloves Project's gloves (http://theglovesproject.com/category/diy/) by a group at ITP Camp in June, 2013.

We made one right-hand glove each.

The ArduIMU sketch is a modification of the ArduIMU code (http://code.google.com/p/ardu-imu/downloads/list) rather than The Gloves Project's sketch (https://github.com/SebMadgwick/ArduIMU-Gloves).

The Max patch reads the gloves sensor data, auto-calibrates, scales the numbers to a midi range (0-127) and sends it out as midi data either locally or over a network.

Still to do as of September 2013:
- program the LED and motor on the glove for feedback
- create a way to store midi setup in the Max patch