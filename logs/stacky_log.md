# Worklog

## Week 1

- (Monday 06.07.2026 8:00 - 11:15) (3,25 Hours) Implemented a basic machine with support for push, pop and addition.
- (Tuesday 06.07.2026 9:00 - 11:05) (2,083 Hours) Added more arithmetic instructions, byte code can now written to a file and read back into the vm.
- (Wednesday 07.07.2026 9:30 - 10:30) (1 Hour) Added function to load assembler file from disk and first example.
- (Thursday 08.07.2026 10:00 - 12:00) (2 Hour) Bug hunting split_by_delimiter did not work as expected.
- (Friday 09.07.2026 10:00 - 11:15) (1,25 Hours) Add bytecode compiler.

## Week 2

- (Monday 13.07.2026 10:00 - 11:40) (1,67 Hours) Add CLI interface and Jump directives to the virtual machine. Documented the Opcodes
- (Tuesday 14.07.2026 10:00 - 11:30) (1,5 Hours) Add compare function for strings and new instructions (duplicate, jump equal, jump not equal). Updated the README in the repositories.
- (Wednesday 15.07.2026 10:00 - 11:10) (1,17 Hours) Add logic to handle parser errors to the compiler, more documentation added.
- (Thursday 16.07-2026 10:10 - 11:30) (1,33 Hours) Add more conditional jumps (lower, lower equal, bigger, bigger equal), a comparision instruction and struct for handling datatypes like strings and bools.
- (Friday 17.07.2026 9:57 - 11:37) (1,67 Hours) Started work on store instruction.

## Week 3

- (Monday 20.07.2026 10:30 - 11:10) (0,62 Hours) Add store instruction and parse it.
- (Monday 20.07.2026 16:15 - 17:32) (1,82 Hours) More logic for string storage added.
- (Tuesday 21.07.2026 10:00 - 11:13) (1,22 Hours) Removed a unnecessary new keyword 'store'. Changed the logic so that push can store data into the data segment.
- (Wednesday 22.07.2026 10:00 - 11:38) (1,63 Hours) Started to work on support for static 64-bit value arrays.
- (Thursday 23.07.2026 10:00 - 11:00) (1,00 Hours) Finished work on array implementation.
- (Friday 24.07.2026 10:13 - 11:42) (1,48 Hours) Started work on read instruction.
- (Monday 27.07.2026 10:00 - 11:00) (1 Hour) Planned the elements index feature, added documentation.
- (Tuesday 28.07.2026 10:30 - 11:34) (1,07 Hours) Developing the pointer table, and checking if the outputted format is correct.
- (Wednesday 29.07.2026 10:00 - 11:00) (1 Hour) the read instruction is now using the pointer table to read the correct element. Changed some design decisions.
- (Thursday 30.07.2026 10:18 - 11:12) (0,9 Hours) Implemented the exchange instruction, planned and implemented a sum example, started working on write instruction
- (Friday 31.07.2026 10:15 - 11:15) (1 Hour) Implemented write opcode, add a sum loop example and change compare and jump instructions to pop values instead of only peeking them.

## Week 4

- (Monday 03.08.2026 10:00 - 11:08) (1,13 Hours) Added more instructions, fixed a bug and enhanced the documentation. Setup the GitHub workflow for building and generating an artifact.
- (Tuesday 04.08.2026 10:15 - 11:30) (1,25 Hours) Fixed a bug, that prevented the sum_loop example from running as expected, added a new loop construct.
- (Wednesday 05.08.2026 10:15 - 11:15) (1 Hour) Added length opcode, expanded the documentation and started planning a bytecode parser that is independent from the actual c-structures data.
- (Friday 07.08.2026) (1,58 Hours) Started working on a portable byte code format.

## Week 5

- (Monday 10.08.2026) (1 Hour) Implemented the platform agnostic byte code format, added more documentation.
