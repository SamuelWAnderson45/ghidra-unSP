# SLEIGH spec for u'nSP

A SLEIGH specification for disassembling/decompiling u'nSP binaries with Ghidra. Incomplete and under development.

## Status
A large number of instructions are implemented. The difference between 1.0, 1.1, etc isn't clear, so this spec is probably some hybrid of all of them. In particular, instructions with the extended register set are not implemented. Decompiler output is quite ugly, particularly operations on pointers. Still usable in many cases.

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
