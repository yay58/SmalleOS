# SmalleOS

   _____                 _       ____   ____   ____  
  / ____|               | |     / __ \ |  _ \ / __ \ 
 | (___   __ _  ___  ___| | ___| |  | || |_) | |  | |
  \___ \ / _` |/ _ \/ __| |/ _ \ |  | ||  _ <| |  | |
  ____) | (_| |  __/ (__| |  __/ |__| || |_) | |__| |
 |_____/ \__, |\___|\___|_|\___|\____/ |____/ \____/ 
          __/ |                                      
         |___/                                       


yaml
Copy code

![SmalleOS Demo](smalleos.gif)

## Overview

SmalleOS is a tiny **bootable terminal OS** (512 bytes) made by **DBS**.  
It runs in emulators like QEMU and can also be booted from a floppy image in VirtualBox.  

---

## Commands

Currently, only the following command works:

dir

yaml
Copy code

- `dir` → shows a list of fake files.  

Other commands (`cls`, `ver`, `help`) are planned but not functional in this version.  

---

## How to boot

### Using QEMU:
```bash
qemu-system-x86_64 -fda smalleos.img
Using VirtualBox:
Create a 1.44MB floppy image.

Write smalleos.img to the first sector.

Attach the floppy image as a boot device.

Start the VM.

Made by DBS
All work done by DBS.
