"BOOTLOADER.asm" is 1. stage bootloader. It loads 2nd stage bootloader into memory and jumps into it.

2nd stage bootloader is "..\KERNEL\KERNEL_ENTRY.asm". It reads memory, sets up 32-bit mode and jumps to 32-bit kernel entry. 