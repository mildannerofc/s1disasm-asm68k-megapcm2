# Sonic 1 GitHub ASM68K with Mega PCM 2
This is a complete translation of the [Sonic 1 GitHub AS Mega PCM 2](https://github.com/vladikcomper/s1disasm-megapcm2) implementation, but now adapted for ASM68K and loosely based on Hivebrain's disassembly from 2005 (Due to having identical parts in code).

You can use this repository as good example for implementing Mega PCM 2 (On Sonic 1 GitHub ASM68K) but you should better take a look on original guide and following how Mega PCM 2 is installed in this disassembly.

If you want to see the original Mega PCM 2 implementation, you can check the [Sonic 1 GitHub AS](https://github.com/vladikcomper/s1disasm-megapcm2) repository.

**Please note:** This project may not be a secure base for your own ROM hacks and modern projects (Even team project or not).

Mega PCM 2 and the Error Handler were created by vladikcomper.

## Known Issues
*	It's widely rumored that you can adapt Mega PCM for ASM68K by replacing periods (`.`) with at-symbols (`@`), but this approach may be problematic.
*	According to vladikcomper, ASM68K is slower than Macro AS.
*	The implementation may differ significantly from the current ASM68K disassembly.

## Original installation guides
- [Sonic 1 GitHub AS - Mega PCM 2 Instalation](https://github.com/vladikcomper/MegaPCM/blob/2.x/docs/1-installation/Sonic-1-Github-AS.md)
- [Sonic 1 Hivebrain 2005 - Mega PCM 2 Installation](https://github.com/vladikcomper/MegaPCM/blob/2.x/docs/1-installation/Sonic-1-Hivebrain-2005.md)
- [Advanced Mega PCM 2 integration for Sonic 1 GitHub AS disassembly](https://github.com/vladikcomper/MegaPCM/blob/2.x/docs/2-advanced-integration/Sonic-1-Github-AS.md)

If you find a fix for any of these issues, please submit a pull request, and I will handle it.

Original disassembly used is [Sonic 1 GitHub ASM68K Branch](https://github.com/sonicretro/s1disasm/tree/asm68k)
