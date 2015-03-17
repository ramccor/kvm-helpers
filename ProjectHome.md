kvm-helpers is a package of helpful command line utilities for users of QEMU/KVM virtual machines.

## Features ##

**qemu-monitor**: A non-interactive command line monitor for KVM virtual machines. Monitors over unix domain sockets or named pipes.  All monitor commands are available. See QEMU/Monitor documentation for full command list.

**qemu-if**: A simple bash script for use with qemu-system command line options -net script= and downscript=

Scripts were originally tested on qemu-kvm-0.12.3 and perl 5.10.1 on a linux kernel version 2.6.32 system.