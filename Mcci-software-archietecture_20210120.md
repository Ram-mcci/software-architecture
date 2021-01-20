# SOFTWARE ARCHITECTURE DOCUMENTATION
[Application layer](#Application-layer)

[Libraries](#libraries)

[Hal](#Hal)

[Firmware](#Firmware)


## Application layer
1. This is the area where an user builts the application. 
2. They simply calls the function.


## Libraries
When the function is called the libraries have that definition of that particular function.

## Hal
1. Hal(Hardware abstraction layer) is nothing but it is the programming layer interfaced with hardware devices.
2. The main purpose of hardware abstraction layer is to allow software run on the hardware. 
3. It is the intermediate of hardware and software . 
4. When a hardware and kernel communicate the hardware abstraction layer translates the information back and forth. 
5. Here in Hal the library just addressed what task should Hal do. 
6. In hal there is a register(memory) , a bit will be set as 0 or 1.
7.  Libraries contain the definition and it assign task to Hal. 
8. Hal gets the information and then communicating to the device.

## Firmware
Firmware is the software above what we did should be taken as a package, that is known as Firmware.





