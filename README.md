# Mega Man Xtreme 2 Weapon Refill Patch
This patch for Mega Man Xtreme 2 on the Gameboy Color makes weapon energy refill upon death in the whole game. 
A detailed description can be found [on the RomHacking page of this hack](http://www.romhacking.net/hacks/4828/), as well as an alternative download link.
In this README you will find further information on how this patch was made and reference material.

## Tools
- [The BGB emulator](http://bgb.bircd.org/#downloads), for disassembly, hex editing, memory viewing, testing and even breakppoints.
- [LunarIPS](https://www.romhacking.net/utilities/240/), to create a patch file.

## Process
The process was actually much the same as the Xtreme 1 patch.
Difference being a loop implemented and the Giga Crush weapon had it's own unique Maximum value.

## References
In order to write the code a lot of knowledge was required. Here I list the sources specifically used for this project.
A big thanks for the people behind these to make Z80 gameboy programming more accessible.
- [A visual opcode map for the gameboy Z80.](http://pastraiser.com/cpu/gameboy/gameboy_opcodes.html)
- [Detailed descriptions for the opcodes, which were confusing to me without it.](https://raw.githubusercontent.com/gb-archive/salvage/master/txt-files/gb-instructions.txt)
- [The full gameboy memory map explanation.](http://gameboy.mongenel.com/dmg/asmmemmap.html)
