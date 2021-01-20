# SOFTWARE ARCHITECTURE DOCUMENTATION
[Application layer](#Application-layer)

[Libraries](#libraries)

[Hal](#Hal)

[Firmware](#Firmware)


## Application layer
This is the area where an user builts the application. They simply calls the function.


## Libraries
When the function is called the libraries have that definition of that particular function.

## Hal
Hal(Hardware abstraction layer) is nothing but it is the programming layer interfaced with hardware devices. The main purpose of hardware abstraction layer is to allow software run on the hardware. It is the intermediate of hardware and software . When a hardware and kernel communicate the hardware abstraction layer translates the information back and forth. Here in Hal the library just addressed what task should Hal do. In hal there is a register(memory) , a bit will be set as 0 or 1. Libraries contain the definition and it assign task to Hal. Hal gets the information and then communicating to the device.

## Firmware
Firmware is the software above what we did should be taken as a package, that is known as Firmware.





