# Obsession 75% Keyboard

A 75% keyboard powered by RP2040.

## Bootloader

To enter bootloader mode:
- Double press the reset button on the PCB
- The keyboard will appear as a USB mass storage device

## Compiling

To compile the firmware:

```bash
qmk compile -kb obsession/ansi_75 -km default
```

## Flashing

After entering bootloader mode:
1. Copy the compiled firmware (.uf2 file) to the USB mass storage device
2. The keyboard will automatically restart with the new firmware

## Layout

The keyboard uses a standard 75% ANSI layout with:
- 6.25u spacebar
- 2u backspace
- 2.25u left shift
- 1.75u right shift
- 2.25u enter
# ANSI_75
