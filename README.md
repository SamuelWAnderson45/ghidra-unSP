# SunPlus µnSP module for Ghidra

A Ghidra module for disassembling/decompiling µnSP binaries. Incomplete and under development.

## Status
A large number of instructions are implemented. The SLEIGH spec was made without access to any official documentation, so it is some hybrid of all of the various versions (1.0, 1.1, 1.2, 1.3, 2.0). In particular, instructions with the extended register set are not implemented. Decompiler output is quite ugly, particularly operations on pointers. Still usable in many cases.

### TODO
- Eliminate unimpl
- Update cs correctly
- Cleanup decompiler output
- Find a way to handle far pointers in the decompiler
- Get the decompiler to recognize switch statements with jump tables
- Implement push/pop fully
- Revisit interrupts and related instructions
- Revisit multiplication
- Fix display for some instructions
- Investigate differences between 1.0, 1.1, 1.2, and 2.0

## Build
Either build using the GhidraDev plugin for Eclipse
or
```
GHIDRA_INSTALL_DIR=path/to/ghidra gradle
```
where gradle is a gradle 7.x version in your PATH.