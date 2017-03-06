MS3 to Serial Port Adapter
==========================

What is this?
-------------

This repo contains a PCB design project including schematic, board layout, and component library.
The board is meant to provide an interface between three connectors:

* The DB15 connector (aka "VGA connector") attached to a Microscan MS3 barcode reader
* A DB9 connector plugged into the RS-232 "serial" port of a PC (or a USB-to-Serial converter or some other device with serial port)
* A 5.5mm center positive 5V DC power supply cable

When all three connectors are plugged in, the barcode reader is powered and can be communicated with from the PC.
For how to communicate with the barcode reader, please refer to Microscan's user manual or use [Microscan's ESP software](http://www.microscan.com/esp-easy-setup-program-software).
The Python library [microscan-driver](https://github.com/jonemo/microscan-driver) might be of use.

The files were created using Autodesk's Eagle 7.6.0.

Compatibility
-------------

I offer no guarantees that this PCB design works or
The board is almost certainly compatible with other Microscan barcode reader products, but it has only been tested with the MS3.

Sources
-------

The component library in this repo contains many footprints that are copied or modified from [Sparkfun's Eagle footprint library](https://github.com/sparkfun/SparkFun-Eagle-Libraries/).
