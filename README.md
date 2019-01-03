# TeensyCam-HW
Hardware design of TeensyCam - a stereo camera module based on MT9V034 sensor and Teensy3.6 microcontroller board.

Created using Altium Designer software suite.

![TeensyCam stereo camera module](https://github.com/icboredman/TeensyCam-HW/blob/master/teensycam_front_tiny.jpg)

#### _Status:_
* mature (more-or-less)

## Features:
* Built using [MCUXpresso IDE](http://www.nxp.com/mcuxpresso/ide/download) 10.2
* Runs on [Teensy 3.6](https://www.pjrc.com/store/teensy36.html) microcontroller board attached to TeensyCam module
* Configures two connected MT9V034 imaging sensors via I2C interface
* Triggers simultaneous image capture, hardware synchronized
* Stereo baseline: 8 cm
* Resolution: 720 x 480 (vertical can be reduced to save bandwidth)
* Image format: raw, uncompressed, 10 bits per dot (monochrome)
* Interface: single USB 2.0 high speed port, CDC device profile
* Power: through USB, 150 mA
* Horizontal field of view: 105°
* Speed: 30 FPS max (configurable)
* Exposure control: pre-set or automatic
* Analog gain control: pre-set or automatic
* Compounding mode control
* Configurable number of lines to send to host

Module schematics diagram: [PDF](https://github.com/icboredman/TeensyCam-HW/blob/master/Project%20Outputs%20for%20Camera/Printouts/Schematic%20Prints.PDF)

Teensy3.6 USB high speed device mode connetion diagram: [PNG](https://github.com/icboredman/TeensyCam-HW/blob/master/Schematic36_USBHS.png)


---
More info in my blog page: https://BoredomProjects.net/index.php/projects/robot-navigation-using-stereo-vision-part-2
