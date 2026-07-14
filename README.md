# general

Short introduction and overview of all my personal projects. If you are a recruiter start here! I will add more projects
to the list over the next few weeks.

All projects are made by hand no AI Models were involved in the development, if research was necessary AI might be involved
to explain domain specific terminology.


## new projects

All new projects in my repositories have some constraints:

- the project needs to be finished in the time of one work week (40 hours)
- public releases are available as an AppImage or Executable
- container based releases should be available as well
- all projects are documented

### Virtual-Machine (Stack based) 

A stack based virtual machine

Language: C

Dependencies: None

Features: virtual machine that is Turing complete, an assembly language which is translated into bytecode

Start: 06.07.2026

Work log:
 - (Monday 06.07.2026 8:00 - 11:15) (3,25 Hours) Implemented a basic machine with support for push, pop and addition
 - (Tuesday 06.07.2026 9:00 - 11:05) (2,083 Hours) Added more arithmetic instructions, byte code can now written to a file and read back into the vm
 - (Wednesday 07.07.2026 9:30 - 10:30) (1 Hour) Added function to load assembler file from disk and first example
 - (Thursday 08.07.2026 10:00 - 12:00) (2 Hour) Bug hunting split_by_delimiter did not work as expected
 - (Friday 09.07.2026 10:00 - 11:15) (1,25 Hours) Add bytecode compiler
 - (Monday 13.07.2026 10:00 - 11:40) (1,67 Hours) Add CLI interface and Jump directives to the virtual machine. Documented the Opcodes
 - (Tuesday 14.07.2026 10:00 - 11:30) (1,5 Hours) Add compare function for strings and new instructions (duplicate, jump equal, jump not equal). Updated the README in the repository

Work time: 12,75 Hours

Time left: 27,25 Hours

Status: __in progress__

Link: [stacky-the-friendly-vm](https://github.com/grewek/stacky-the-friendly-vm)
## old projects

### Gameboy Emulator

A Gameboy emulator written in Rust with builtin debugger.

Features: Z80-CPU-Emulation, Debugger and Disassembler

Dependencies: EGUI

Status: Incomplete and currently on hold

Link: [gboyrust](https://github.com/grewek/gboyrust)

### KForth

A Forth implementation in C 

Features: virtual machine, forth lexer, forth parser

Dependencies: None,

Status: Incomplete and currently on hold

Link: [kforth](https://github.com/grewek/kforth)

### KRaytrace

A Raytracer written in C\#

Dependencies: None,
Status: Complete

Link: [kraytrace](https://github.com/grewek/kraytrace)

### Dielectric Dreams

A Fantasy Console, implementation of my own ISA (Instruction Set Architecture) implemented in Rust

Dependencies: None
Status: Incomplete and currently on hold

Link: [dielectric dreams](https://github.com/grewek/dielectric_dreams)

### Cacao OS 

An operating system for x86_64 with custom bootloader.
Dependencies: None

Link: [cacaoos](https://github.com/grewek/cacaoos)
