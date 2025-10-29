# Game Boy Emulator (C++)

A fully working Game Boy emulator written in C++.
It implements the CPU, memory map, graphics, timers/interrupts, cartridge loading, and input (enough to play Game Boy games end-to-end). 

## Features

* LR35902 CPU: full instruction set with interrupts
* Memory-mapped I/O, timers (DIV/TIMA/TMA/TAC), DMA
* PPU: background/window/sprite rendering with VBlank/STAT timing
* Joypad input and savable cartridges (battery RAM where supported)
* CLI options for scaling, FPS cap, and basic logging

## Status

* **Works:** Gameplay, rendering, timing, input
* **In Progress:** Audio Output

## Controls (default)

* D-Pad: Arrow keys
* A: Z B: X
* Start: Enter Select: Backspace
* Pause: P Reset: R Quit: Esc
