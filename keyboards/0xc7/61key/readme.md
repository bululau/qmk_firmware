# 61Key

![61Key](https://i.imgur.com/HdE6c6zh.jpeg)

Custom keyboard designed by RealEmanGaming aka 0xC7

* Keyboard Maintainer: [0xC7](https://github.com/RealEmanGaming)
* Hardware Supported: ATMega32u4
* Hardware Availability: N/A (private board, might open source)

Make example for this keyboard (after setting up your build environment):

    make 0xc7/61key:default

Flashing example for this keyboard:

    make 0xc7/61key:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Press and hold the key at (2,4) in the matrix (usually enter) and press the key at (4,2) in the matrix (usually dot)
* **Physical reset button**: Briefly press the button on the back of the PCB
* **Keycode in layout**: Press the key mapped to `RESET` if it is available
