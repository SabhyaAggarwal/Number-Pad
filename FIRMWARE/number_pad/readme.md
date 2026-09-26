# number_pad

A 5x4 numpad built around an RP2040 (Pro Micro / Pico style footprint).

* Keyboard Maintainer: [Sabhya Aggarwal](https://github.com/SabhyaAggarwal)
* Hardware Supported: RP2040 (Pro Micro ATmega32U4 pin-compatible controller)
* Hardware Availability: https://github.com/SabhyaAggarwal/Number-Pad

Make example for this keyboard (after setting up your build environment):

    qmk compile -kb number_pad -km default

Flashing example for this keyboard:

    qmk flash -kb number_pad -km default

See [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) then the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information.

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (top left key, `Num`) and plug in the keyboard
* **Physical reset button**: Briefly press the reset button on the back of the PCB
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
