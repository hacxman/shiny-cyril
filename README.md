CPU
===

Homebrew (hackerspacebrew) 8bit CPU. MISC type as there are only 6 instructions
(except nop) and each can be conditional. With sixteen 8bit registers, mmaped IO,
no pipelining and no superscalarity.

Files:
------

 * cpu.circ is [logisim](http://ozark.hendrix.edu/~burch/logisim/) schematic
 * instr.txt contains ISA sketch
 * mem.txt contains preliminary memory layout

Subprojects:
------------

* [freezing-adventure](https://github.com/hacxman/freezing-adventure) is a very primitive assembler for this CPU
* [laughing-bugfixes](https://github.com/hacxman/laughing-bugfixes) is an emulator
