# Computer architecture (microprocessor) comparison

I will be comparing **ARMv2** and **MIPS R2000** architectures.


## Table of contents
- [History](#history)
- [Physicalities](#physicalities)
- [Architecture type](#architecture-type)
- [N-address](#n-address)
- [Registers](#registers)
- [Flags](#flags)
- [Data width](#data-width)
- [Memory layout](#memory-layout)
- [Virtual memory](#virtual-memory)
- [ISA](#isa)
- [Addressing modes](#addressing-modes)
- [IO](#io)
- [Interrupts](#interrupts)
- [Data types](#data-types)
- [Speed](#speed)
- [Cache](#cache)
- [Aplication](#application)
- [Software](#software)
- [Emulators](#emulators)
- [Sources](#sources)



## History

### ARMv2

ARM originally stood for Acorn RISC Machine, but later renamed to Advanced RISC Machines. Arm Holdings develops instruction set architectures (ISAs) and licenses them to others. The first version was tested on 26 April 1985. The latest version that is used in products is ARMv9.2-A.

### MIPS R2000

This architecture (microprocessor) was developed by MIPS Computer Systems in 1986. It was the first commercial implementation of the RISC architecture. R2000 users included Ardent Computer, DEC, Silicon Graphics, Northern Telecom and MIPS's own Unix workstations.



## Physicalities

### ARMv2

### MIPS R2000

It used integrated circuits as it's elementary base and they had large scale integration. The die had 110,000 transistors and the size was 80mm<sup>2</sup>. I couldn't find information about it's power consumption, but a similar chip from MIPS used 10W.



## Architecture type

### ARMv2

### MIPS R2000

It was a load/store architecture, which means all instructions operated on the registers, except the load/store incstructions used to access memory.



## N-address

### ARMv2

### MIPS R2000

It used one, two, three address instruction formats.



## Registers

### ARMv2

### MIPS R2000

It had thirty-two (32) 32-bit general-purpose registers and three (3) 32-bit special registers: *pc* (program counter) that always contains the address of the next instruction to be executed; *hi* and *lo* hold the result of multiplication or division.



## Flags

### ARMv2

### MIPS R2000

As far as I found out, it didn't have any flags. The later released MIPS IV ISA had flags.



## Data width

### ARMv2

### MIPS R2000

It had a machine word width of 32 bits.



## Memory layout

### ARMv2

### MIPS R2000

It had continuous byte-addressable memory, that was using a 32-bit address. This means it could have had a maximum of 4GB of memory. The layout consisted of reserved data, program text, static data, the heap and the stack.



## Virtual memory

### ARMv2

### MIPS R2000

Virtual memory was supported.



## ISA

### ARMv2

### MIPS R2000

It used the MIPS I instruction set architecture (ISA). It had 18 arithmetic, 6 shift, 8 muliplication/division, 12 load/store, 12 jump and branch and 16 other instructions, a total of 72 isntructions. The ISA had three types: R - register, I - immediate, and J - jump.



## Addressing modes

### ARMv2

### MIPS R2000

It had one addressing mode: base + offset. The effective address is the offset + content of the specified base register.



## IO

### ARMv2

### MIPS R2000

It had SPIM Input, which allowed reading from the keyboard and SPIM Output, which allowed printing to the console.



## Interrupts

### ARMv2

### MIPS R2000

When an event happened, the address of the instruction that was about to be executed was saved into a special register *EPC*. The interrupt event was handled and the saved instruction was loaded back and continued execution.



## Data types

### ARMv2

### MIPS R2000

It had three data types: a byte, halfword (2 bytes), and word (4 bytes). 



## Speed

### ARMv2

### MIPS R2000

It was available in 8.3, 12.5, and 15 MHz grades. Later an improved version was released, the R2000A. It had two grades of 12.5 and 16.67 MHz. It had a coefficient of instructions per cycle of 1.



## Cache

### ARMv2

### MIPS R2000

It used fast standard SRAM chip cache with one-cycle read latency.



## Application

### ARMv2

### MIPS R2000

The MIPS R2000 microporcessor was used by Ardent Computer, Silicon Graphics, Northern Telecom and MIPS (company) own workstations.



## Software

### ARMv2

### MIPS R2000

I found little information on the softweare that was written for this architecture.



## Emulators

### ARMv2

### MIPS R2000

SPIM. Versions before 7.0 implemented MIPS I ISA, which was used by MIPS R2000. [Emulator](https://spimsimulator.sourceforge.net/)



## Sources

Sources can be found [here](sources.md).