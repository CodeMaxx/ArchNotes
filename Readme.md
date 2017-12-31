# ArchNotes

## Lab 1

- [Instruction Format](https://www.cs.umd.edu/class/sum2003/cmsc311/Notes/Mips/format.html)

- [Wikibook MIPS Instruction format (with opcodes)](https://en.wikibooks.org/wiki/MIPS_Assembly/Instruction_Formats)

- The destination is upper half last 5 bits.

- [Opcode](http://www.linfo.org/opcode.html) - Highest 6 bits of the machine code

- The `div` instruction stores the remainder in $HI and quotient in $LO. These two registers are not directly accessible in instructions.
We need to use [`mfhi` and `mflo` instructions](http://chortle.ccsu.edu/assemblytutorial/Chapter-14/ass14_5.html).

- Most of the R-type instructions have 0x00 opcode. They are identified by their "function code" which is the last 6 bits of the machine code.

- [How to load 32 bit values in a register?](https://www.cs.umd.edu/class/sum2003/cmsc311/Notes/Mips/load32.html)

- [Pseudo-instructions](https://www.cs.umd.edu/class/sum2003/cmsc311/Notes/Mips/pseudo.html)

## Preparing for Tut 4

- [add v/s addu](https://stackoverflow.com/questions/16634110/difference-between-add-and-addu)

- [Advantage of 2's complement over 1's complement](https://stackoverflow.com/questions/11054213/advantage-of-2s-complement-over-1s-complement)

- [Sign and Zero Extension](https://www.wikiwand.com/en/Sign_extension)

- [FAQ - Load and Store instruction](https://stackoverflow.com/questions/7226147/clarifications-on-signed-unsigned-load-and-store-instructions-mips)

## Lab 4

- [How to write a procedure in MIPS](http://www.poslarchive.com/math/misc/mips-asm.html)

## Lab 5

- [Exceptions in MIPS](http://www.cs.iit.edu/~virgil/cs470/Labs/Lab7.pdf)
- SPIM stores and displays data in the format(little or big endian) of the host machine
