# 10Dollar DIY Flight Controller BLACKPILL-STM32F411CEU6


![My Remote Image](https://youtu.be/VZH03NSljEk)?dl=0)

To verify pin assignments: Open Configurator, in CLI - type "resource". 

No warranties. Use at your own risk especially the MPU6050.

Do tests with no propellers attached.

Recommended Settings:

ESC Dshot300 with Bluejay Firmware 48Khz - Remember your ESC version (better download a copy) first before Upgrading.

set looptime = 1000

Changes from Original MatekF411 Target:

Swapped SoftSerial1_RX and LED-STRIP pins.

Replaced SBUS by IBUS as default protocol.

BMI160 as default IMU versus MPU6000.

![My Remote Image](https://github.com/EonClaw/10Dollar-Flight-Controller-STM32F411CEU6/blob/main/20221011_154746-ed.jpg?dl=0)


![My Remote Image](https://github.com/EonClaw/10Dollar-Flight-Controller-STM32F411CEU6/blob/main/blackpill-fc-pinout.png?dl=0)
