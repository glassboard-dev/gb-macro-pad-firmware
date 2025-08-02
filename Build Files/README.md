# gb_macropad Build Files

## List of Builds and updates:
- **Build 1.0** - Initial build of gb_macropad firmware. 
    - Adds core functionality, support for VIA configurator, and hard-coded encoder functionality on the first layer.
    - The hard-coded configuration for the encoders is:
        - Left/Right Scrolling on the Left Encoder
        - Volume Up/Down on the Right Encoder
    - The pushbutton function on the encoders is currently not implemented, however it is a planned feature for future builds, along with configuration of the encoder functions.

## Entering the Bootloader

Enter the bootloader in 2 ways:

* **Physical reset button**: While the device is connected to your computer, flip it upside down. hold down the "Boot" button and press the "RESET" button briefly, then release the "BOOT" button.
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available

### If the firmware has not yet been flashed to the device, you will need to use QMK Toolbox.

## Flashing firmware using QMK Toolbox
1. Download QMK Toolbox from the [QMK Website](https://qmk.fm/toolbox)
2. Download the most recent .hex file
3. Open QMK Toolbox
4. Enter the bootloader using the above instructions. Ensure that QMK Toolbox recognizes that the device is in the bootloader mode - you should see yellow text that a ATMEGA32u4 device has been connected.
5. Open the build file in QMK toolbox and hit the "Flash" button. Do not unplug the macro pad until it has indicated that it has been properly flashed. 