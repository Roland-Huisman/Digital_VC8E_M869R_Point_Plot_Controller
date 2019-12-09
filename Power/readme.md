The VC8E board set needs a symmetrical -15V and +15V power supply. There are a few options to connect the power for the analog circuits to the board.

Personally I use the option 1. There are GND, +15V and -15V connections on the backplane to power the Omnibus backplane. I've made a cable to connect these to my M869 board.

If you prefer you can use the GND, +15V and -15V connections on the M869 board itself. (option 2)

But you can also use a normal external power supply for this -15V and +15V. (option 3)

The official way is to connect a High Quality external power supply for the -15V and +15V. (option 3)
This original power had even a feedback loop. So it regulates the voltage directly on the M869 board.
In this case you have two GND wires, two -15V wires and two +15V wires.

