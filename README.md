# WinIOCTLtest


Windows Driver Model (WDM)
This is a quick exercise that demonstrates how to:
- Create a simple WDM kernel mode driver, that can receive and respond to a custom defined input/output control code (IOCTL) sent in from a userland program
- Create a simple userland program that can sent a custom defined IOCTL to the kernel driver
- Pass some data from the userland program to the kernel driver via DeviceIoConctrol
- Pass some data back from the kernel to the userland program
- Reference: https://www.ired.team/miscellaneous-reversing-forensics/windows-kernel-internals/sending-commands-from-userland-to-your-kernel-driver-using-ioctl
