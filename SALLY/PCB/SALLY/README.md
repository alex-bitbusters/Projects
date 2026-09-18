# SALLY PCB Placeholder

KiCad PCB project files for the Atari XE Sally adapter are TBD. The reused `65xx.lib` and `65xx.dcm` library files are copied to `SALLY/PCB/` from the MCL64 reference project as a starting point.

For now, future schematic work should treat those libraries as generic placeholders: use the generic 6502-family symbols only as a starting point, and plan to add or adapt a Sally-specific symbol so the dedicated `/HALT` signal and Atari XE pinout expectations are captured explicitly instead of inheriting a 6502/6510 assumption.
