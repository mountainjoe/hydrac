hydrac
======

C library/program for controlling CH Robotics Hydra smart power supply


Usage
=====

First ensure you have serial connectivity. You likely need to download
and install the USB-to-UART chip (CP2104) driver here:

    http://www.silabs.com/products/mcu/pages/usbtouartbridgevcpdrivers.aspx

After which, you'll need to plug in your hydra and look for an appropriate 
serial device. On my mac, the hydra serial interface showed up as 
`/dev/tty.SLAB_USBtoUART`. This will be the device argument to hydrac. 
