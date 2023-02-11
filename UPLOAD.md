How to enable DFU mode

![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/bluepill_button.jpg?dl=0)

Use the onboard BOOT0 and NRST button to put the board into bootloader mode:

    Connect to PC USB port
    press and hold the BOOT0 button
    press and release NRST (reset) button to power cycle the processor
    release BOOT0 button
    
    OR
    
    While disconnected, press hold BOOT0 button, connect to USB port, then release BOOT0 button.

Upload firmware using Configurator while in DFU mode.


Configurator Links

https://github.com/iNavFlight/inav-configurator/releases/tag/6.0.0-RC2

https://github.com/iNavFlight/inav-configurator/releases/tag/6.0.0-RC1

https://github.com/iNavFlight/inav-configurator/releases/tag/6.0.0-FP2

https://github.com/iNavFlight/inav-configurator/releases/tag/5.1.0


