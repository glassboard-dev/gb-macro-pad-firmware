# gb_macropad

A 3x4 macropad with 2 rotary encoders, designed and built by Glassboard Product Development.

Contributors:
* Quinlan Walinder - PCB Schematic & Design,  Firmware
* Colin Ternus - PCB Schematic, Mechanical Design

Additional Information:

* Keyboard Maintainer: [quinlanwalinder-gb](https://github.com/quinlanwalinder-gb)
* Hardware Supported: ATmega32u4
* Layout: 3x4 matrix + 2 encoders

### If the firmware has not yet been flashed to the device, you will need to use QMK Toolbox and the most recent .hex file in the [Build Files Directory](/Build%20Files/).

## Setup

In order to configure the keymap for gb_macropad, go to  [the VIA configuration webapp](https://usevia.app/).

Because the device has not yet been registered with VIA, you will have to manually set up the configuration GUI. In order to do this, enter the "Settings" tab of the webapp and enable the "Show Design Tab" option. A new tab should pop up with a paintbrush icon - this is the design tab. Navigate to the design tab and upload the "via.json" file located in the [gb_macropad firmware folder](/gb_macropad/). If prompted, allow the webapp to connect to the HID device labelled "gb_macropad". Now, when in the "Configure" tab, the layout should match that of the macro pad and allow for customization of the keybindings.

