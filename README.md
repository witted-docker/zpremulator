# zpremulator
Emulator enviroments working out of the box with zpr framework.  
Every image includes an openssh server with user `root`, password `root`.

Use `/usr/sbin/sshd -D -p 20122` to start the included server on port 20122


Remember to install `qemu` and `binfmt` for arm architecture support on x86_64 systems.

- `x86_64-minimal`: includes just the openssh server
- `x86_64`: includes zeromq and some extra libs such as numpy, i2c-tools,...

- `arm-minimal`: includes just the openssh server
- `arm`: includes zeromq and some extra libs such as numpy, i2c-tools,...
  
  


© Copyright 2020 Witted Srl - All Rights Reserved
