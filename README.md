# MEDUSAs Embedded System Toolkit

This collection of static compiled embedded binaries can be used for research, security testing and debugging on embedded devices.
It is derived from the MEDUSA Scalable Firmware Runtime (https://medusa.cyberdanube.com), which can be used for firmware emulation.
The static compiled tools in this repository are ordered by CPU architecture and instruction set to provide the security community quick access to the right binary.

### &check; done
### &cross; under construction

## The following binaries are compiled in a static way:
- strace &check;
- gdbserver &check;
- gdb &check;
- bash &check;
- ncat &check;
- perl &check;
- socat &check;
- tcpdump &check;
- busybox &check;

#### Busybox includes:
- netstat &check;
- ifconfig &check;
- sh &check;
- ash &check;
- telnetd &cross;
- dd &cross;
- nc &check;

## The following architectures and instruction sets are covered:
- ARM 32 Bit Version 5 Little Endian Soft Float (ARM32v5le) &check;
- ARM 32 Bit Version 5 Big Endian Soft Float (ARM32v5be) &cross;
- ARM 32 Bit Version 5 Little Endian Hard Float (ARM32v5lehf) &check;
- ARM 32 Bit Version 5 Big Endian Hard Float (ARM32v5behf) &cross;
- ARM 32 Bit Version 7 Little Endian Soft Float (ARM32v7le) &check;
- ARM 32 Bit Version 7 Big Endian Soft Float (ARM32v7be) &cross;
- ARM 32 Bit Version 7 Little Endian Hard Float (ARM32v7lehf) &check;
- ARM 32 Bit Version 7 Big Endian Hard Float (ARM32v7behf) &cross;
- MIPS 32 Bit Release 2 Little Endian (MIPS32v2le) &check;
- MIPS 32 Bit Release 2 Big Endian (MIPS32v2be) &check;
- MIPS 64 Bit Release 2 Little Endian (MIPS64v2le) &cross;
- MIPS 64 Bit Release 2 Big Endian (MIPS64v2be) &cross;
- PowerPC 32 Bit Little Endian (PPC32le) &cross;
- PowerPC 32 Bit Big Endian (PPC32be) &check;
- PowerPC 64 Bit Little Endian (PPC64le) &cross;
- PowerPC 64 Bit Big Endian (PPC64be) &cross;
- SPARC 32 Bit Little Endian (SPARC32le) &cross;
- SPARC 32 Bit Big Endian (SPARC32be) &cross;
- SH4 32 Bit Little Endian (SH432le) &cross;
- SH4 32 Bit Big Endian (SH432be) &cross;
- ix86 Little Endian (ix86le) &check;
- ix86_64 Little Endian (ix86_64le) &cross;

## Contributors

* [Sebastian Dietz][2] of [CyberDanube][1]
* [Thomas Weber][3] of [CyberDanube][1]


[1]: https://cyberdanube.com
[2]: https://github.com/fitfrost4
[3]: https://github.com/Tom435
