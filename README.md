## Adafruit Feather RP2040 Adalogger - 8MB Flash with microSD Card - STEMMA QT / Qwiic PCB

<a href="http://www.adafruit.com/products/5980"><img src="assets/5980.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit Feather RP2040 Adalogger - 8MB Flash with microSD Card - STEMMA QT / Qwiic. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5980

### Description

This is the Adafruit Feather RP2040 Adalogger - our take on an 'all-in-one' RP2040 data-logger (or data-reader) with built-in USB, battery charging, and a microSD holder ready to rock! [We have other boards in the Feather family, check'em out here](https://www.adafruit.com/feather)

The RP2040 Adalogger is the same size and shape as a Feather and is intended to make your next data logging or data reading project super easy. Micro SD card socket wired for SPI or SDIO? Yes! STEMMA QT / Qwiic connector for fast I2C? Of course! Neopixel? It's a-glowin' This board will work excellently with Arduino or CircuitPython/MicroPython for any data recording/retreiving projects.

At the Feather's heart is an RP2040 chip, clocked at 133 MHz and at 3.3V logic, the same one used in the Raspberry Pi Pico. This chip has a whopping 8MB of onboard QSPI FLASH and 264K of RAM! This makes it great for buffering and processing data before writing it to the SD card.

To make it easy to use for portable projects, we added a connector for any of our 3.7V Lithium polymer batteries and built-in battery charging. You don't need a battery, it will run just fine straight from the USB Type C connector. But, if you do have a battery, you can take it on the go, then plug in the USB to recharge. The Feather will automatically switch over to USB power when it's available.

Here're some handy specs! You get:

* Measures 2.0" x 0.9" x 0.28" (50.8mm x 22.8mm x 7mm) without headers soldered in
* Light as a (large?) feather - 6.3 grams
* RP2040 32-bit Cortex M0+ dual core running at ~133 MHz @ 3.3V logic and power
* 264 KB RAM
* 8 MB SPI FLASH chip for storing files and CircuitPython/MicroPython code storage. No EEPROM
* Tons of GPIO! 21 x GPIO pins with following capabilities:
* Four 12-bit ADCs (one more than Pico)
* Two I2C, Two SPI, and two UART peripherals, we label one for the 'main' interface in standard Feather locations
* 16 x PWM outputs - for servos, LEDs, etc
* Built-in 200mA+ lipoly charger with charging status indicator LED
* Pin #13 red LED for general purpose blinking
* RGB NeoPixel for full-color indication.
* MicroSD card holder for adding as much storage as you could possibly want for reading or writing. Connected to the 'second' SPI port on pins 18, 19, 20 and card select on 23. Optional card detect line can be connected to pin 15. For advanced hackers who want to use 4-bit SDIO, we connect DAT1 and DAT2 to 21 and 22 - note we do not have Arduino or CircuitPython code for this mode.
* On-board STEMMA QT connector that lets you quickly connect any Qwiic, STEMMA QT or Grove I2C devices with no soldering!
* Both Reset button and Bootloader select button for quick restarts (no unplugging-replugging to relaunch code)
* USB Type C connector lets you access built-in ROM USB bootloader and serial port debugging
* 3.3V Power/enable pin
* 4 mounting holes
* 12 MHz crystal for perfect timing.
* 3.3V regulator with 500mA peak current output

Comes assembled and tested, with some header. You'll need a soldering iron to attach the header for installing onto your Feather. Stacking headers will let you put another FeatherWing on top. Lipoly battery, MicroSD card, and USB cable not included (but we do have lots of options in the shop if you'd like!)

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
