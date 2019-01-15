# NPKC 17 Switch Tester alternative PCB
Alternative PCB to convert the NPKC 17 switch tester (https://www.massdrop.com/buy/npkc-switch-tester?mode=guest_open or https://www.massdrop.com/buy/npkc-17-switch-tester?mode=guest_open) into a number pad. It is small enough to be modified by the free version of [EAGLE](https://cadsoft.io/).

The Atmel ATmega32U2 microcontroller can be programmed with both [TMK keyboard firmware](https://github.com/tmk/tmk_keyboard) and [QMK keyboard firmware](https://github.com/qmk/qmk_firmware). TMK code for this PCB can be found [here](https://github.com/VinnyCordeiro/tmk_keyboard/tree/master/keyboard/AUNK_Numpad), while the QMK code (and a standard number pad firmware) is now available here.

As of January 15, 2019, the design is still untested.

Updates
-------
#### 13/September/2016
Initial release. Included are all custom libraries for EAGLE.

#### 15/January/2019
Uploaded a tentative firmware made with the help of [Keyboard Firmware Builder](https://kbfirmware.com/). Design still untested.
