# zmk-config

Sofle Choc wireless on nRF52840 (nice!nano v2 compatible boards).

GitHub Actions builds the firmware on every push. Download the `.uf2` artifacts and flash each half:

1. Plug a half via USB-C
2. Double-tap reset to enter bootloader (a USB drive appears)
3. Drag the matching `.uf2` onto the drive
4. Repeat for the other half

`settings_reset.uf2` clears stored BT pairings if you need to re-pair the halves.
