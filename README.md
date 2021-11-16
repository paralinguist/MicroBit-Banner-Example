# MicroBit-Banner-Example
Example code for creating a scrolling banner from multiple MicroBits

DISCLAIMER:
This code was written by students back in 2017. I suspect it had to be tweaked to get it to work in the real world, and those tweaks are gone :-(

1) The first MicroBit in your array will need to run the controller code - you can adjust the message here.
2) Subsequent MicroBits (designated agents) will each need an assigned address
3) When run, each MicroBit will display their character in turn before broadcasting the next character in the chain

This can probably be much more efficiently executed in the more modern implementations available on Makecode - the principle remains the same (each microbit has an assigned address and displays their character in turn before broadcasting to the next one)
