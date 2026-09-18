# SALLY PCB Placeholder

KiCad PCB project files for the Atari XE Sally adapter are TBD. This `SALLY/PCB/SALLY/` directory is reserved for the future project-specific KiCad files, while the shared `65xx.lib` and `65xx.dcm` library files live one level up in `SALLY/PCB/` as the current starting point copied from the MCL64 reference project.

For now, future schematic work should treat those libraries as generic placeholders: use the generic 6502-family symbols only as a starting point, and plan to add or adapt a Sally-specific symbol so the dedicated `/HALT` signal and Atari XE pinout expectations are captured explicitly instead of inheriting a 6502/6510 assumption.
