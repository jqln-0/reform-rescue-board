This is a breakout board for an MNT Reform's SOM! It's designed to make it
easier to rescue a bad bootloader flash, or work on the initial bring-up of new
SOMs.

Most of what it breaks out is already available on the Reform motherboard,
however USB1 is exposed as a micro usb port so that it's easy to use
manufacturer tools like `uuu` that rely on USB OTG functionality.

Here is what the PCB looks like in KiCad:

![](images/1.png?raw=true)

Here is what the PCB looks like in real life:

![](images/2.jpg?raw=true)

Here is what an assembled board that's in-use looks like:

![](images/3.jpg?raw=true)

(please excuse my bodges; I initially used one wrong part number + one wrong
footprint.)

Note the last picture includes the little STL in `enclosure/`. It's not very
good, but whatever. It'll do.
