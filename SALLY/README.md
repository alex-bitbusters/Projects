# SALLY

MicroCore Labs SALLY is a Teensy 4.1-based cycle-accurate emulator for the 6502C "Sally" CPU used in Atari XE computers such as the 65XE and 130XE.

## Key differences from MCL64 / 6510

- No internal 6510 zero-page I/O port at `$00/$01`; Sally zero page is treated as normal memory/bus traffic.
- Dedicated `/HALT` input support to release the bus independently of `RDY`.
- Sally/Atari-oriented pinout notes and a generic whole-address-space shadow RAM model instead of C64-specific BASIC/KERNAL banking.

## Source

The main cycle-accurate emulator source is in [`SourceCode/Cycle_Accurate_6502C/SALLY.ino`](SourceCode/Cycle_Accurate_6502C/SALLY.ino).

## Credits

This project is based on Ted Fried's MicroCore Labs MCL64 project for the MOS 6510.
