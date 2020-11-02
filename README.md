# zpremulator
Emulator enviroments working out of the box with zpr framework.  
Every image includes an openssh server with user `emulator`, password `emulator` (and `root` user with password `root`).

Use `/usr/sbin/sshd -D -p 20122` to start the included server on port 20122


Remember to install `qemu` and `binfmt` for arm architecture support on x86_64 systems.

- `x86_64-minimal`: includes just the openssh server
- `x86_64`: includes zeromq and some extra libs such as numpy, i2c-tools,...
- `arm-minimal`: includes just the openssh server
- `arm`: includes zeromq and some extra libs such as numpy, i2c-tools, htop, valgrind...

**NB:** In order to build the Dockerfiles in this folder, you need to have **qemu-aarch64-static** and **qemu-arm-static** in the same folder. You can find them in **/usr/bin/qemu.....**.



© Copyright 2020 Witted Srl - All Rights Reserved