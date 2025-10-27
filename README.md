# Sonic 1 GitHub ASM68K with Mega PCM 2
This is a complete translation of the Sonic 1 GitHub AS Mega PCM implementation, adapted for ASM68K and loosely based on Hivebrain's disassembly from 2005.

If you want to see the original Mega PCM 2 implementation, you can check the [Sonic 1 GitHub AS](https://github.com/vladikcomper/s1disasm-megapcm2) repository.

After implementing Mega PCM 2, maybe I still do not plan to create a guide for it (Adding section for Mega PCM 2 integration in Sonic 1 ASM68K Branch from GitHub). I am currently unsure how to translate the implementation guide from AS to ASM68K while maintaining the sound driver's base and structure.

Please note: This project may not be a secure base for your own ROM hacks at this time.

Mega PCM 2 and the Error Handler were created by vladikcomper.

## Known Issues
*	Cheats are not working. (This may be beneficial for your ROM hack if you prefer to prevent tampering.)
*	It's widely rumored that you can adapt Mega PCM for ASM68K by replacing periods (`.`) with at-symbols (`@`), but this approach may be problematic.
*	According to vladikcomper, ASM68K is slower than Macro AS.
*	The implementation may differ significantly from the current ASM68K disassembly.

If you find a fix for any of these issues, please submit a pull request, and I will handle it.

Original disassembly used is [Sonic 1 GitHub ASM68K Branch](https://github.com/sonicretro/s1disasm/tree/asm68k)
