# vocore2-carrier
Carrier board for the vocore 2 that features usb-c input, uart over usb-c, sd card storage, SPI PWM RGB LED driver, and momentary button sensing.

## USB-C Input
5v 3A power supplied over USB-C.

## UART
USB-C supports UART output, so port can be used to both power the device and debug it.

## SD Storage
Internal only, no external port. Up to 2TB. Main storage for all applications outside of main OS.

## RGB LED Controller
Connects over SPI. PWM support. Common anode.

## Momentary Button Sensing
Support for button presses. I2C or SPI, whichever is easier.
