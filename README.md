# $5 DIY Flight Controller BLACKPILL-STM32F411CEU6

[![Watch the video](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/YT-VID-BIG.png)](https://www.youtube.com/embed/4ur5MpvDCFg)

INAV 5.1.0 Firmware

Features:

BMI160 or MPU6500. For MPU6050 I2C (see instructions)


To verify pin assignments: Open Configurator, in CLI - type "resource". 

No warranty. Use at your own risk.

Recommended Settings:

ESC Dshot300 with Bluejay Firmware 48Khz - Remember your ESC version (better download a copy) first before Upgrading.

Type in CLI:

set looptime = 1000

set dshot_beeper_enabled = OFF
           


Prototype with MPU6050

![My Remote Image](https://github.com/EonClaw/10Dollar-Flight-Controller-STM32F411CEU6/blob/main/images/20221008_022133.jpg?dl=0)


Version 1.0 MPU6050 I2C

![My Remote Image](https://github.com/EonClaw/10Dollar-Flight-Controller-STM32F411CEU6/blob/main/images/20221010_202114.jpg?dl=0)

Flyable but performance-wise, not recommended. Let's move on.

Version 2.0 BMI160 SPI

![My Remote Image](https://github.com/EonClaw/10Dollar-Flight-Controller-STM32F411CEU6/blob/main/images/20221014_203524-ed.jpg?dl=0)

![My Remote Image](https://github.com/EonClaw/10Dollar-Flight-Controller-STM32F411CEU6/blob/main/images/20221015_083626.jpg?dl=0)

![My Remote Image](https://github.com/EonClaw/10Dollar-Flight-Controller-STM32F411CEU6/blob/main/images/20221015_083644.jpg?dl=0)

![My Remote Image](https://github.com/EonClaw/10Dollar-Flight-Controller-STM32F411CEU6/blob/main/images/20221015_083927.jpg?dl=0)

![My Remote Image](https://github.com/EonClaw/10Dollar-Flight-Controller-STM32F411CEU6/blob/main/images/20221011_154746-ed.jpg?dl=0)


![My Remote Image](https://github.com/EonClaw/10Dollar-Flight-Controller-STM32F411CEU6/blob/main/images/blackpill-fc-pinout-sd.png?dl=0)

![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/BMI1601.jpeg?dl=0)

![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/MPU6500.png?dl=0)


![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/thumbs/thumb-20220921_230136.jpg?dl=0)
![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/thumbs/thumb-20221009_025947.jpg?dl=0)
![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/thumbs/thumb-20221010_201518.jpg?dl=0)
![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/thumbs/thumb-20221014_203524-ed.jpg?dl=0)
![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/thumbs/thumb-20221014_205547.jpg?dl=0)
![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/thumbs/thumb-20221014_214014.jpg?dl=0)
![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/thumbs/thumb-20221014_214036.jpg?dl=0)
![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/thumbs/thumb-20221015_083626.jpg?dl=0)
![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/thumbs/thumb-20221016_135220.jpg?dl=0)

IMU SELECTION

![My Remote Image](https://github.com/EonClaw/10Dollar-Flight-Controller-STM32F411CEU6/blob/main/IMPORTANT!!!.png?dl=0)

Black Box (SDCARD)

![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/inavbb.png?dl=0)
![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/bbexplorer.png?dl=0)

Other modules used:

Tyro79 frame, strap and motors

20A 4-in-1 ESC (loaded with BlueJay)

Buck converter

Flysky FS-RX2A Pro Receiver (IBUS)

Flysky FS-i6 Transmitter (14-channel Firmware)

Lipo Battery 4s 600mAH

3D Printed Blackpill Mount STL - https://www.thingiverse.com/thing:5567402

![My Remote Image](https://github.com/EonClaw/10Dollar-Flight-Controller-STM32F411CEU6/blob/main/images/blkpil-05-50.png?dl=0)


CAUTION!!!

USING THE MPU6050 AS PRIMARY IMU WILL HAVE A HIGH RISK OF BURNING YOUR MOTORS IF NOT PROPERLY CONFIGURED.




SOON! A 5$ DIY FLIGHT CONTROLLER USING STM32F401.



![My Remote Image](https://github.com/EonClaw/10Dollar-Flight-Controller-STM32F411CEU6/blob/main/images/cc.png?dl=0)
