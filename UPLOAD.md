How to enable DFU mode

![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/bluepill_button.jpg?dl=0)

Use the onboard BOOT0 and NRST button to put the board into bootloader mode:

    Connect to PC USB port
    press and hold the BOOT0 button
    press and release NRST (reset) button to power cycle the processor
    release BOOT0 button
    
    OR
    
    While disconnected, press hold BOOT0 button, then connect to USB port.

Upload firmware using Configurator while in DFU mode.
