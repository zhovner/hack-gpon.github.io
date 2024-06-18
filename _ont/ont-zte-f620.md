---
title: ZTE F620 
has_children: false
layout: default
parent: ZTE
---


# UART Log

```
Boot SPI NAND


U-Boot 2013.04 (Nov 13 2020 - 15:24:19)

CPU  : ZX279128@A9,800MHZ
Board: ZTE zx279128evb
I2C:   ready
DRAM:  128 MiB
com1
_8000000,48000000
product_vid = 25
vid=25-F620
bootsel=3
NAND:  manuid=e5,71

Manu ID: 0xe5, Chip ID: 0x71 (Dosilicon SPI NAND DS35Q1GA 128MiB 3,3V)
128 MiB
<nand_read_skip_bad_,1217>!mtdpart=0x1,offset=0x0,mtdpartoffset=0x180000,mtdPartsize=0x80000,length=0x20000
In:    serial
Out:   serial
Err:   serial
Net:   serdes init done
addr 0x9400004c before value is fffe0000
addr 0x9400004c after value is fffe01ff
eth0

Hit 1 to upgrade software version
Hit any key to stop autoboot:  0
skip bad block...addr=0x140000
skip bad block...addr=0xec0000
addr=1a00000
skip bad block...addr=0x2260000
addr=3a00000
select=0x0
search=0x2
<nand_read_skip_bad_,1217>!mtdpart=0x6,offset=0x0,mtdpartoffset=0x200000,mtdPartsize=0x400000,length=0x1000
tmp=0x00000000, value=0
select=0x0
search=0x2
search->result[0].entry=1a00140
<nand_read_skip_bad_,1217>!mtdpart=0x2,offset=0x0,mtdpartoffset=0x1a00000,mtdPartsize=0x2000000,length=0x1140000
<nand_read_skip_bad_,1237>!Skipping bad block 0x2260000

---mtdparts_init--current_mtd_partnum=0-
dev id: type = 2, num = 0, size = 0xffffffff, mtd_id = single part
part  : name = rootfs0, size = 0x01120000, offset = 0x01a20000
part  : name = rootfs1, size = 0x01060000, offset = 0x03a20000

--- jffs2_part_info: partition number 0 for device nand0 (single part)
jffs2_part_info:rootfs0,1a20000
### JFFS2 loading '0uImage' to 0x44000000
Scanning JFFS2 FS: .  fsload_skip_bad_offset=0x2260000
................ done.
### JFFS2 load complete: 3072340 bytes loaded to 0x44000000
<nand_read_skip_bad_,1217>!mtdpart=0x0,offset=0x0,mtdpartoffset=0x0,mtdPartsize=0x200000,length=0x80000
lseek=0x42048000
cmdline=U-Boot V7.0.10P2N20 20201113153519
output gpio:48, value=1, 0
## Booting kernel from Legacy Image at 44000000 ...
   Image Name:   Linux Kernel Image
   Image Type:   ARM Linux Kernel Image (uncompressed)
   Data Size:    3072276 Bytes = 2.9 MiB
   Load Address: 40008000
   Entry Point:  40008000
   Verifying Checksum ... OK
   Loading Kernel Image ... OK
OK
----------------------
|-->setup versioninfo tag...

Starting kernel ...

Uncompressing Linux... done, booting the kernel.

Boot SPI NAND


U-Boot 2013.04 (Nov 13 2020 - 15:24:19)

CPU  : ZX279128@A9,800MHZ
Board: ZTE zx279128evb
I2C:   ready
DRAM:  128 MiB
com1
_8000000,48000000
product_vid = 25
vid=25-F620
bootsel=3
NAND:  manuid=e5,71

Manu ID: 0xe5, Chip ID: 0x71 (Dosilicon SPI NAND DS35Q1GA 128MiB 3,3V)
128 MiB
<nand_read_skip_bad_,1217>!mtdpart=0x1,offset=0x0,mtdpartoffset=0x180000,mtdPartsize=0x80000,length=0x20000
In:    serial
Out:   serial
Err:   serial
Net:
Boot SPI NAND


U-Boot 2013.04 (Nov 13 2020 - 15:24:19)

CPU  : ZX279128@A9,800MHZ
Board: ZTE zx279128evb
I2C:   ready
DRAM:  128 MiB
com1
_8000000,48000000
product_vid = 25
vid=25-F620
bootsel=3
NAND:  manuid=e5,71

Manu ID: 0xe5, Chip ID: 0x71 (Dosilicon SPI NAND DS35Q1GA 128MiB 3,3V)
128 MiB
<nand_read_skip_bad_,1217>!mtdpart=0x1,offset=0x0,mtdpartoffset=0x180000,mtdPartsize=0x80000,length=0x20000
In:    serial
Out:   serial
Err:   serial
Net:   serdes init done
addr 0x9400004c before value is fffe0000
addr 0x9400004c after value is fffe01ff
eth0

Hit 1 to upgrade software version
Hit any key to stop autoboot:  0
=>
=>
=>
=> help
?       - alias for 'help'
base    - print or set address offset
boot    - boot default, i.e., run 'bootcmd'
bootd   - boot default, i.e., run 'bootcmd'
bootk   - boot kernel
bootm   - boot application image from memory
bootz   - boot Linux zImage image from memory
cmp     - memory compare
coninfo - print console devices and information
cp      - memory copy
dhcp    - boot image via network using DHCP/TFTP protocol
downver - upgrade software downloaded from TFTP server
echo    - echo args to console
fdt     - flattened device tree utility commands
fsinfo  - print information about filesystems
fsload  - load binary file from a filesystem image
go      - start application at address 'addr'
gpiotest- gpiotest dir [num] [in/out]
gpiotest value [num] [1/0]
gpiotest gvalue [num]
help    - print command description/usage
i2c     - I2C sub-system
imxtract- extract a part of a multi-image
itest   - return true/false on integer compare
ls      - list files in a directory (default /)
md      - memory display
mii     - MII utility commands
mt      - memory test
mtddebug- mtddebug operate
mtest   - simple RAM read/write test
mw      - memory write (fill)
nand    - NAND sub-system
ping    - send ICMP ECHO_REQUEST to network host
printenv- print environment variables
reset   - Perform RESET of the CPU
run     - run commands in an environment variable
saveenv - save environment variables to persistent storage
setenv  - set environment variables
sleep   - delay execution for some time
tftp    - boot image via network using TFTP protocol
version - print monitor, compiler and linker version
watchdog- watchdog reset && disable
xmodem  - xmodem
=> <INTERRUPT>
=>
=>
=>
=> <INTERRUPT>
=> <INTERRUPT>
=> <INTERRUPT>
=> <INTERRUPT>
=> <INTERRUPT>
=> <INTERRUPT>
=>
=>
=> version

U-Boot 2013.04 (Nov 13 2020 - 15:24:19)
arm-buildroot-linux-uclibcgnueabi-gcc (Buildroot 2013.02) 4.7.2
GNU ld (GNU Binutils) 2.23.1
=> fsinfo
no version
=> ls /
skip bad block...addr=0x140000
skip bad block...addr=0xec0000
addr=1a00000
skip bad block...addr=0x2260000
addr=3a00000
rootfs_select=0

---mtdparts_init--current_mtd_partnum=0-
dev id: type = 2, num = 0, size = 0xffffffff, mtd_id = single part
part  : name = rootfs0, size = 0x01120000, offset = 0x01a20000
part  : name = rootfs1, size = 0x01060000, offset = 0x03a20000

--- jffs2_part_info: partition number 0 for device nand0 (single part)
jffs2_part_info:rootfs0,1a20000
rootfs0,1a20000
Scanning JFFS2 FS: .  fsload_skip_bad_offset=0x2260000
................ done.
 -rw-r--r--  3072340 Fri Nov 13 07:35:16 2020 0uImage
 drwxr-xr-x        0 Fri Nov 13 07:35:16 2020 bin
 drwxr-xr-x        0 Fri Nov 13 07:23:20 2020 dev
 drwxr-xr-x        0 Fri Nov 13 07:33:37 2020 etc
 drwxr-xr-x        0 Fri Nov 13 07:33:06 2020 home
 -rwxr-xr-x       66 Fri Nov 13 07:23:20 2020 init
 drwxr-xr-x        0 Fri Nov 13 07:35:16 2020 kmodule
 drwxr-xr-x        0 Fri Nov 13 07:35:16 2020 lib
 lrwxrwxrwx       12 Fri Nov 13 07:29:01 2020 linuxrc -> /bin/busybox
 drwxr-xr-x        0 Fri Nov 13 07:23:20 2020 mnt
 drwxr-xr-x        0 Fri Nov 13 07:23:20 2020 proc
 drwxr-xr-x        0 Fri Nov 13 07:23:20 2020 root
 drwxr-xr-x        0 Fri Nov 13 07:35:16 2020 sbin
 drwxr-xr-x        0 Fri Nov 13 07:23:20 2020 sys
 drwxr-xr-x        0 Fri Nov 13 07:23:20 2020 tagparam
 lrwxrwxrwx        7 Fri Nov 13 07:23:20 2020 temp -> var/tmp
 lrwxrwxrwx        7 Fri Nov 13 07:23:20 2020 tmp -> var/tmp
 drwxr-xr-x        0 Fri Nov 13 07:23:20 2020 userconfig
 drwxr-xr-x        0 Fri Nov 13 07:23:20 2020 usr
 drwxr-xr-x        0 Fri Nov 13 07:23:20 2020 var
 drwxr-xr-x        0 Fri Nov 13 07:23:20 2020 wlan
```
