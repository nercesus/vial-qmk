# genesis
<img src="https://github.com/nercesus/genesis/blob/main/images/3.jpg?raw=true" width="35%"/>

A 65% RP2040 based keyboard. Made for the latest version.

* Keyboard Maintainer: [nercesus](https://github.com/nercesus)  
* Hardware Availibility: [genesis](https://github.com/nercesus/genesis)

Make example for this keyboard (after setting up your build environment):

    make genesis/rev2:default

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
