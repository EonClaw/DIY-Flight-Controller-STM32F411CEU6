How to enable DFU mode

![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/bluepill_button.jpg?dl=0)

Use the onboard BOOT0 and NRST button to put the board into bootloader mode:

    Connect to PC USB port
    press and hold the BOOT0 button
    press and release NRST (reset) button to power cycle the processor
    release BOOT0 button
    
    OR
    
    While disconnected, press hold BOOT0 button, connect to USB port, then release BOOT0 button.
    
    OR
    
    While connected to INAv or Betaflight-Configurator, got to CLI and type 
    
    "dfu" for INAV-Configurator or "bl" for Betaflight-Configurator


Upload firmware using Configurator while in DFU mode.


INAV Configurator Links (matched firware version)

https://github.com/iNavFlight/inav-configurator/releases/tag/6.0.0-RC2 

https://github.com/iNavFlight/inav-configurator/releases/tag/6.0.0-RC1

https://github.com/iNavFlight/inav-configurator/releases/tag/6.0.0-FP2

https://github.com/iNavFlight/inav-configurator/releases/tag/5.1.0


BETAFLIGHT Configurator Links

betaflight_4.3.2_BLACKPILL_.hex ===>  https://github.com/betaflight/betaflight-configurator/releases/tag/10.8.0


USING THE STM32CubeProgrammer TO UPLOAD FIRMWARE
![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/upload-1.png?dl=0)


Download Program and lnstall.

https://www.st.com/en/development-tools/stm32cubeprog.html#get-software

![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/upload-2AA-dl.png?dl=0)


Connect Flight Controller cable, Enable DFU Mode, Click USB and Enter.

![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/upload-3-connectusbA.png?dl=0)

Read Chip

![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/upload-4A.png?dl=0)

Full chip erase

![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/upload-5A.png?dl=0)

![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/upload-6A.png?dl=0)

![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/upload-7A.png?dl=0)


Select Firmware to be uploaded - Check Verif and Run after programming - Browse - Start Programming

![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/upload-7B.png?dl=0)

![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/upload-8A.png?dl=0)

After Programming - Close all prompts and exit

![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/upload-9A.png?dl=0)

Open Now Configurator to update settings.
