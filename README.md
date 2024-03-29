# $5 DIY Flight Controller BLACKPILL-STM32F411 (Betaflight and INAV)

FOR LATEST UPDATE ->

https://github.com/ShanGlor/INAV-Blackpill-Flight-Controller


UPDATE (03/06/2023) !!!     INAV 6.0.0 RC2 Firmware V3

inav_6.0.0_RC2_BLACKPILL_QUAD_SS1_SD_LED_4S_ADC2_108

FEATURES: Running @ 108mhz, 2x UARTs, 1x Software_serial, 2x SPIs, 1x I2C, 2x ADC.
4x Motors + 4x Servos, LED Strip, SDCard as Blackbox, Voltage Sensor, Beeper, Telemetry.

![My Remote Image](https://github.com/EonClaw/10Dollar-Flight-Controller-STM32F411CEU6/blob/main/images/blackpill-fc-pinout-LARGE-rev3-QUAD-inav.png?dl=0)

HOOKUP DIAGRAM V3
![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/blackpill-fc-pinout-LARGE-rev2-QUADa.png?dl=0)




Betaflight 4.3.2 Firmware  - Use Rev2 Hookup Diagram

FEATURES: 2x UARTs, 2x Software_serial, LED Strip, SDCard Blackbox, Voltage-current Sensor, Beeper, Telemetry.

![My Remote Image](https://github.com/EonClaw/10Dollar-Flight-Controller-STM32F411CEU6/blob/main/images/betaflight432-480.png?dl=0)

[![Watch the video](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/YT-VID-BIG.png)](https://www.youtube.com/embed/4ur5MpvDCFg)

BUILD IMAGES

![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/thumbs/thumb-20220921_230136.jpg?dl=0)
![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/thumbs/thumb-20221009_025947.jpg?dl=0)
![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/thumbs/thumb-20221010_201518.jpg?dl=0)
![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/thumbs/thumb-20221014_203524-ed.jpg?dl=0)
![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/thumbs/thumb-20221014_205547.jpg?dl=0)
![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/thumbs/thumb-20221014_214014.jpg?dl=0)
![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/thumbs/thumb-20221014_214036.jpg?dl=0)
![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/thumbs/thumb-20221015_083626.jpg?dl=0)
![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/thumbs/thumb-20221016_135220.jpg?dl=0)

Blackbox SD Card Support

![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/inavbb2.png?dl=0)

![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/bbexplorer.png?dl=0)

https://github.com/iNavFlight/blackbox-log-viewer/releases

SUPPORTED/TESTED SENSORS

Acc/Gyro: MPU6000, MPU6500, MPU9250, BMI160 and MPU6050 (see instructions below).

Baro: BMP280, MS5611

Mag: HMC5883, QMC5883 

Rangefinder: VL53l0x

GPS: BN-220T

MPU6050 (Only on Inav-5.1.0 with headers facing front) - Click "Keep Current Settings" after flashing otherwise it will not boot. Modify "Mixers" to QUADX then "Outputs" to Enable Motors and Servo Output and DSHOT300.

Please use firmware - > inav_5.1.0_BLACKPILL_108.hex

![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/keepcurrentsettings.png?dl=0)


OTHERS

Tyro79 frame, strap and motors

20A 4-in-1 ESC (loaded with BlueJay Firmware)

Buck converter adjusted to 5v output

DIY ELRS TX/RX modules

Flysky FS-RX2A Pro Receiver (IBUS)

Flysky FS-i6 Transmitter ERFLY6 firmware

Lipo Battery 4s 600mAH

3D Printed Blackpill Mount STL - https://www.thingiverse.com/thing:5567402

![My Remote Image](https://github.com/EonClaw/10Dollar-Flight-Controller-STM32F411CEU6/blob/main/images/blkpil-05-50.png?dl=0)

No warranties. No guarantees. Use at your own risk. 

![My Remote Image](https://github.com/EonClaw/10Dollar-Flight-Controller-STM32F411CEU6/blob/main/images/cc.png?dl=0)

Please See Updated Post at

https://github.com/ShanGlor/Blackpill-F411-Flight-Controller
