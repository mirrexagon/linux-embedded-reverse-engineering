```
[nix-shell:~/Downloads/3g17wn]$ binwalk ntc_3g17wn_1.0.52.0.dat

DECIMAL       HEXADECIMAL     DESCRIPTION
--------------------------------------------------------------------------------
0             0x0             uImage header, header size: 64 bytes, header CRC: 0x5D60F010, created: 2011-10-13 03:57:27, image size: 4313024 bytes, Data Address: 0x80000000, Entry Point: 0x802F6000, data CRC: 0x4A9BAEC3, OS: Linux, CPU: MIPS, image type: OS Kernel Image, compression type: lzma, image name: "Linux Kernel Image"
64            0x40            LZMA compressed data, properties: 0x5D, dictionary size: 33554432 bytes, uncompressed size: 3222268 bytes
1048576       0x100000        Squashfs filesystem, little endian, non-standard signature, version 3.0, size: 3263820 bytes, 801 inodes, blocksize: 65536 bytes, created: 2011-10-13 03:57:24
```
