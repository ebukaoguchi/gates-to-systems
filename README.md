# From Gates to Systems

An interactive site for digital logic, computer architecture, and operating systems: build circuits, wire a breadboard, step assembly, and run the simulators. Every concept is shown as something you can touch, not text to read.

**Live:** https://ebukaoguchi.github.io/gates-to-systems/

## What is inside

- **Circuits** — a gate lab (NOT, AND, OR, XOR, NAND, NOR, XNOR) with animated signal flow and an optional timing view (per-gate propagation delays, total delay, critical-path highlighting), half and full adders, a 4-bit ripple adder, a multiplier, a restoring divider, sequential logic (latches, flip-flops, counters, shift registers, RAM), combinational blocks (multiplexers, decoders, a 4-bit ALU), a Karnaugh-map minimiser, and a free-build sandbox where your own designs become reusable chips.
- **Breadboard** — the full adder wired from real 7486 / 7408 / 7432 chips, with switches, LEDs, probing, and a simulated multimeter.
- **Advanced** — labelled motherboard and CPU explorers, a components library, applied projects (traffic-light controller, soil monitoring, and more), Arduino C projects with line-stepped sketches and a serial monitor, a digital modulation studio, a switch-bounce and debounce lab, and a tools bench (number trainer, voltage divider, RC and 555 calculators, ADC visualiser).
- **Systems** — a MIPS assembly lab with a debugger, an x86-64 / MIPS / ARM comparison in lockstep, datapath, cache, and pipeline explorers, an address-decoding and memory-mapped I/O lab, and operating-systems simulators (scheduling including MLFQ, page replacement, Banker's algorithm, memory allocation, address translation with TLB, disk scheduling).
- **Course labs** — full guided lab tracks for Operating Systems (11 labs, plus an OS-in-C series: fork, pthreads, semaphores, pipes), Computer Architecture (10 labs, ending in a simple 8-bit CPU), and Computer Organization (7 design labs), each with auto-checked tasks.

A Beginner / Advanced toggle changes depth, not content: Beginner is guided and plain, Advanced adds netlists, expressions, registers, and datasheet detail. Four colour themes. Progress and saves live only on the visitor's device; there are no accounts.

## Running it

It is a single self-contained page: open `index.html` in a browser, or visit the live link above.

## Licence

MIT — see [LICENSE](LICENSE). Designed and built by Ebuka Philip Oguchi.
