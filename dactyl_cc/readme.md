# Dactyl-CC

![DactylCC](https://github.com/ppp3ppj/keyboard-config/blob/main/things/dactyl_cc/dactyl_cc_preview.jpeg)

Modelled on the *Kinesis Advantage* (KA) 1|2, though missing it's combined function and program row, the *Dactyl CC* retains the finger and thumb key placements of the KA but opts to split board into physical halves.

* Keyboard Maintainer: [Michael Johns](https://github.com/mjohns)
* Hardware Supported: Pro micro controller or clones of
* Hardware Availability: [Dactyl CC GitHub](https://github.com/mjohns/dactyl-cc)

Make example for this keyboard (after setting up your build environment):

    make handwired/dactyl_cc:default

Flashing example for this keyboard:

    make handwired/dactyl_cc:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
