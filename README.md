# Danger Zone

A small kernel demo for the Atari 2600

<img src="Images/DangerZone_Title.png" alt="Title" width="320"/> <img src="Images/DangerZone_Game.png" alt="Game" width="320"/>

## Building

From the command line:

    dasm DangerZone.asm -oDangerZone.bin -f3

Alternatively, the included makefile can be used. Before building, in the makefile adjust the paths `DASM` and (optionally) `STELLA`. To compile just type `make`, or `make run` in order to build and then load the ROM in Stella.

## On 8bitworkshop.com

You can build and run this project in [8bitworkshop](http://8bitworkshop.com/redir.html?platform=vcs&file=DangerZone.asm&githubURL=https://github.com/sehugg/DangerZone/tree/master/Source).

## Links

[DASM](https://sourceforge.net/projects/dasm-dillon) macro assembler

[Stella](https://stella-emu.github.io) Atari 2600 VCS emulator
