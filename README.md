# TeensyCam-HW
Hardware design of TeensyCam - a stereo camera module based on MT9V034 sensor and Teensy3.6 microcontroller board.

![TeensyCam stereo camera module](https://github.com/icboredman/TeensyCam-HW/blob/master/teensycam_front_tiny.jpg)

#### _Status:_
* mature (more-or-less)

## Features:
* Created using [Altium Designer](https://www.altium.com/altium-designer/) software suite
* Main components: two MT9V034 imaging sensors + [Teensy 3.6](https://www.pjrc.com/store/teensy36.html) microcontroller board
* Hardware synchronized simultaneous image capture
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
