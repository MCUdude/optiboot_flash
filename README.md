# Optiboot flash
Optiboot is an easy to install bootloader for the Arduino environment.

### Key features:
* Small in size (512B)
* Supports baudrates upto 1Mbit
* Supports write to flash within application
* Compatible with LOTS of AVR microcontrollers

## Supported devices
* [ATmega640, ATmega1280, ATmega2560](https://github.com/MCUdude/MegaCore)
* [ATmega64, ATmega128, ATmega1281, ATmega2561](https://github.com/MCUdude/MegaCore)
* [ATmega8535, ATmega16, ATmega32, ATmega164A/P, ATmega324A/P/PA, ATmega644/P, ATmega1284/P](https://github.com/MCUdude/MightyCore)
* [ATmega8515, ATmega162](https://github.com/MCUdude/MajorCore)
* [ATmega8, ATmega88/P, ATmega168/P, ATmega328/P](https://github.com/MCUdude/MiniCore)
* [ATmega169/P, ATmega329/P, ATmega649/P](https://github.com/MCUdude/ButterflyCore)
* ATmega3290/P, ATmega6490/P

## Building from source
You need to install `make`, `avr-libc`, `avr-binutils` and `avr-gcc`. [This guide](http://maxembedded.com/2015/06/setting-up-avr-gcc-toolchain-on-linux-and-mac-os-x/) contains everything you need for MacOS and Linux.

To build bootloaders for all supported devices, simply run `$ ./makeall`.

## Acknowledgements

> Although it has evolved considerably, Optiboot builds on the original work of Jason P. Kyle (stk500boot.c), <br/>
[Arduino group (bootloader)](http://arduino.cc), [Spiff (1K bootloader)](http://spiffie.org/know/arduino_1k_bootloader/bootloader.shtml),
[AVR-Libc group](http://nongnu.org/avr-libc) and [Ladyada (Adaboot)](http://www.ladyada.net/library/arduino/bootloader.html).

> Optiboot is the work of Peter Knight (aka Cathedrow). Despite some misattributions, it is not sponsored or supported by any organisation or company including Tinker London, Tinker.it! and Arduino. <br/>
> Maintenance of optiboot was taken over by Bill Westfield (aka WestfW) in 2011. <br/>
> Flash write functionality added by [majekw](https://github.com/majekw/) in 2015.
