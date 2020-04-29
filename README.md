# Creator-Studio-app-SSL-pinning-bypass
well, the creator studio app does an ssl pinning on a native library called libcoldstart.so.  
pull that library, libcoldstart.so and analyze its code with ghidra or IDA pro.

Tools I used when patching:

1. Ghidra, for viewing disassembled library's binaries.

2. Hexeditor for editing the library.

in the repository I have pushed both modified and original library.

the original has the extension .bak, I made a backup of it while I was trying to modify it.

**original one** : https://github.com/mAshraf9/Creator-Studio-app-SSL-pinning-bypass/blob/master/libcoldstart.so.bak

**modified one** : https://github.com/mSharif10/Creator-Studio-app-SSL-pinning-bypass/blob/master/libcoldstart.so
