# Creator-Studio-app-SSL-pinning-bypass
well, the creator studio app does an ssl pinning on a native library called libcoldstart.so.  
pull that library, libcoldstart.so and analyze its code with ghidra or IDA pro.

Tools I used when patching:

1. Ghidra, for viewing disassembled library's binaries.

2. Hexeditor for editing the library.


**patched lib v3.0.0.4.6 ** : https://github.com/mSharif10/Creator-Studio-app-SSL-pinning-bypass/blob/master/libcoldstart.so
