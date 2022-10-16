# 10$ DIY Flight Controller BLACKPILL-STM32F411CEU6

INAV 5.1.0 Firmware

To verify pin assignments: Open Configurator, in CLI - type "resource". 

No warranties. Use at your own risk especially the MPU6050.

Do tests with no propellers attached.

Recommended Settings:

ESC Dshot300 with Bluejay Firmware 48Khz - Remember your ESC version (better download a copy) first before Upgrading.

set looptime = 1000


Changelog from Original MatekF411 Target:

10/14/2022:

            Swapped SoftSerial1_RX and LED-STRIP pins.

            Replaced SBUS by IBUS as default protocol.

            BMI160 as default IMU versus MPU6000.
            
10/16/2022:

            Renamed "inav_5.1.0_BLACKPILL_BMI160.hex" to "inav_5.1.0_BLACKPILL_BMI160_96Mhz-old.hex" - to reflect systemclock.
            
            Added "inav_5.1.0_BLACKPILL_BMI160_96Mhz-new.hex" that runs at 96Mhz but on a different permutation.           
            


Prototype with MPU6050

![My Remote Image](https://github.com/EonClaw/10Dollar-Flight-Controller-STM32F411CEU6/blob/main/20221008_022133.jpg?dl=0)


Version 1.0 MPU6050

![My Remote Image](https://github.com/EonClaw/10Dollar-Flight-Controller-STM32F411CEU6/blob/main/20221010_202114.jpg?dl=0)

![My Remote Image](https://github.com/EonClaw/10Dollar-Flight-Controller-STM32F411CEU6/blob/main/20221011_154746-ed.jpg?dl=0)


Version 2.0 BMI160

![My Remote Image](https://github.com/EonClaw/10Dollar-Flight-Controller-STM32F411CEU6/blob/main/20221014_203524-ed.jpg?dl=0)

![My Remote Image](https://github.com/EonClaw/10Dollar-Flight-Controller-STM32F411CEU6/blob/main/20221015_083626.jpg?dl=0)

![My Remote Image](https://github.com/EonClaw/10Dollar-Flight-Controller-STM32F411CEU6/blob/main/20221015_083644.jpg?dl=0)

![My Remote Image](https://github.com/EonClaw/10Dollar-Flight-Controller-STM32F411CEU6/blob/main/20221015_083927.jpg?dl=0)

![My Remote Image](https://github.com/EonClaw/10Dollar-Flight-Controller-STM32F411CEU6/blob/main/blackpill-fc-pinout.png?dl=0)

IMU SELECTION
![My Remote Image](https://github.com/EonClaw/10Dollar-Flight-Controller-STM32F411CEU6/blob/main/IMPORTANT!!!.png?dl=0)

Others:

Tyro79 frame, strap and motors

20A 4-in-1 ESC (loaded with BlueJay)

Flysky FS-RX2A Pro Receiver (IBUS)

Flysky FS-i6 Transmitter (14-channel Firmware)

Lipo Battery 4s 600mAH

3D Printed Blackpill Mount STL - https://www.thingiverse.com/thing:5567402

![My Remote Image](https://github.com/EonClaw/10Dollar-Flight-Controller-STM32F411CEU6/blob/main/blkpil-05.png?dl=0)


CAUTION!!!

USING THE MPU6050 AS PRIMARY IMU WILL HAVE A HIGH RISK OF BURNING YOUR MOTORS IF NOT PROPERLY CONFIGURED.




SOON! A 5$ DIY FLIGHT CONTROLLER USING STM32F401.
