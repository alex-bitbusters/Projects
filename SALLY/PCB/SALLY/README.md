# SALLY PCB Placeholder

KiCad PCB project files for the Atari XE Sally adapter are TBD. This `SALLY/PCB/SALLY/` directory is reserved for the future project-specific KiCad files, while the shared `65xx.lib` and `65xx.dcm` library files live one level up in `SALLY/PCB/` as the current starting point copied from the MCL64 reference project.

For now, future schematic work should use the generic `6502` symbol from the shared library as the temporary CPU entry point in the SALLY adapter project, with the dedicated `/HALT` connection and Atari XE pinout differences called out in the schematic notes until a Sally-specific symbol is added.
