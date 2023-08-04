# keeb_x3

![3D render showing the "keeb-x3" used layout](https://i.imgur.com/OkPvd4L.jpeg)

*these firmware files are for a 96% / 1800-style ortholinear keyboard named "keeb-x3" which have it's cad files hosted on a [Codeberg repo](https://codeberg.org/wanesty/keeb-x3) and is lisenced under the [Nonviolent Public License](https://thufie.lain.haus/NPL.html)*

* Keyboard Maintainer: [wanesty](https://gockin.me)
* Hardware Supported: [custom pcb](https://codeberg.org/wanesty/keeb-x3) using the rp2040

Make example for this keyboard (after setting up your build environment):

    make keeb_x3:via

Flashing example for this keyboard:

    make keeb_x3:via:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 2 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard.
* **Physical reset button**: Briefly press three times the `RESET` button on the back of the PCB.