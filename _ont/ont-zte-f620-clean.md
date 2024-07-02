---
title: ZTE F620 clean from ebay
has_children: false
layout: default
parent: ZTE
---


# UART Log

```
Boot SPI NAND


U-Boot 2013.04 (Feb 23 2019 - 11:06:13)

CPU  : ZX279128@A9,800MHZ
Board: ZTE zx279128evb
I2C:   ready
DRAM:  128 MiB
com1
8000000,48000000
product_vid = 25
vid=25-F620
bootsel=3
NAND:  manuid=c8,1

Manu ID: 0xc8, Chip ID: 0x01 (ESMT SPI NAND F50L1G41LB 128MiB 3,3V)
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
addr=1a00000
addr=3a00000
select=0x0
search=0x2
<nand_read_skip_bad_,1217>!mtdpart=0x6,offset=0x0,mtdpartoffset=0x200000,mtdPartsize=0x400000,length=0x1000
tmp=0x00000000, value=0
select=0x0
search=0x2
search->result[0].entry=1a00140
<nand_read_skip_bad_,1217>!mtdpart=0x2,offset=0x0,mtdpartoffset=0x1a00000,mtdPartsize=0x2000000,length=0x1020000

---mtdparts_init--current_mtd_partnum=0-
dev id: type = 2, num = 0, size = 0xffffffff, mtd_id = single part
part  : name = rootfs0, size = 0x01000000, offset = 0x01a20000
part  : name = rootfs1, size = 0x01000000, offset = 0x03a20000

--- jffs2_part_info: partition number 0 for device nand0 (single part)
jffs2_part_info:rootfs0,1a20000
### JFFS2 loading '0uImage' to 0x44000000
Scanning JFFS2 FS: ................. done.
### JFFS2 load complete: 3033900 bytes loaded to 0x44000000
<nand_read_skip_bad_,1217>!mtdpart=0x0,offset=0x0,mtdpartoffset=0x0,mtdPartsize=0x200000,length=0x80000
lseek=0x42047000
cmdline=U-Boot V7.0.10P2T21 20190223111911
output gpio:48, value=1, 0
## Booting kernel from Legacy Image at 44000000 ...
   Image Name:   Linux Kernel Image
   Image Type:   ARM Linux Kernel Image (uncompressed)
   Data Size:    3033836 Bytes = 2.9 MiB
   Load Address: 40008000
   Entry Point:  40008000
   Verifying Checksum ... OK
   Loading Kernel Image ... OK
OK
----------------------
|-->setup versioninfo tag...

Starting kernel ...

Uncompressing Linux... done, booting the kernel.
Booting Linux on physical CPU 0
Linux version 3.4.110 (root@A23176683) (gcc version 4.7.2 (Buildroot 2013.02) ) #99 SMP Sat Feb 23 11:18:56 CST 2019
CPU: ARMv7 Processor [414fc091] revision 1 (ARMv7), cr=18c53c7d
CPU: PIPT / VIPT nonaliasing data cache, VIPT aliasing instruction cache
Machine: ZTE ZX279128 (Device Tree), model: ZTE ZX279128
Memory policy: ECC disabled, Data cache writealloc
======= zx_map_io ====pdt_mem_size=8000000===
BUG: mapping for 0x00400000 at 0xf0000000 out of vmalloc space
BUG: mapping for 0x00800000 at 0xf0100000 out of vmalloc space
BUG: mapping for 0x00a20000 at 0xf0200000 out of vmalloc space
BUG: mapping for 0x00c00000 at 0xf0300000 out of vmalloc space
BUG: mapping for 0x94000000 at 0xf0400000 out of vmalloc space
BUG: mapping for 0x94100000 at 0xf0500000 out of vmalloc space
BUG: mapping for 0x94200000 at 0xf0600000 out of vmalloc space
BUG: mapping for 0x94400000 at 0xf0700000 out of vmalloc space
BUG: mapping for 0x9a100000 at 0xf0800000 out of vmalloc space
BUG: mapping for 0x00d00000 at 0xf0900000 out of vmalloc space
BUG: mapping for 0x92000000 at 0xf4000000 out of vmalloc space
BUG: mapping for 0x00200000 at 0xf0a00000 out of vmalloc space
BUG: mapping for 0x9fe00000 at 0xf0f00000 out of vmalloc space
BUG: mapping for 0x09100000 at 0xf0b00000 out of vmalloc space
BUG: mapping for 0x09400000 at 0xf0c00000 out of vmalloc space
BUG: mapping for 0x09300000 at 0xf0d00000 out of vmalloc space
BUG: mapping for 0x09200000 at 0xf0e00000 out of vmalloc space
BUG: mapping for 0x46700000 at 0xf1000000 out of vmalloc space
[CLK] zx279128 clk init ok.
PERCPU: Embedded 7 pages/cpu @c06fd000 s6592 r8192 d13888 u32768
Built 1 zonelists in Zone order, mobility grouping on.  Total pages: 32512
Kernel command line: console=ttyS0,115200n8 root=/dev/mtdblock9 ro rootfstype=jffs2 mem=128M; U-Boot V7.0.10P2T21 20190223111911 0x1a00000 0x0 0x82
PID hash table entries: 512 (order: -1, 2048 bytes)
Dentry cache hash table entries: 16384 (order: 4, 65536 bytes)
Inode-cache hash table entries: 8192 (order: 3, 32768 bytes)
Memory: 128MB = 128MB total
Memory: 96108k/96108k available, 34964k reserved, 0K highmem
Virtual kernel memory layout:
    vector  : 0xffff0000 - 0xffff1000   (   4 kB)
    fixmap  : 0xfff00000 - 0xfffe0000   ( 896 kB)
    vmalloc : 0xc8800000 - 0xf0000000   ( 632 MB)
    lowmem  : 0xc0000000 - 0xc8000000   ( 128 MB)
    modules : 0xbf000000 - 0xc0000000   (  16 MB)
      .text : 0xc0008000 - 0xc0549cdc   (5384 kB)
      .init : 0xc054a000 - 0xc05709c0   ( 155 kB)
      .data : 0xc0572000 - 0xc05ae2e0   ( 241 kB)
       .bss : 0xc05ae304 - 0xc05f7ac8   ( 294 kB)
Hierarchical RCU implementation.
        Additional per-CPU info printed with stalls.
NR_IRQS:16 nr_irqs:16 16
sched_clock: 31 bits at 25MHz, resolution 40ns, wraps every 85899ms
zxic zx279128 system timer initialized
console [ttyS0] enabled
[UART]register_console: zx29 console registered!
Calibrating delay loop... 1594.16 BogoMIPS (lpj=7970816)
pid_max: default: 32768 minimum: 301
Mount-cache hash table entries: 512
CPU: Testing write buffer coherency: ok
CPU0: thread -1, cpu 0, socket 0, mpidr 80000000
smp_twd: clock not found: -2
Calibrating local timer... 399.92MHz.
Setting up static identity map for 0x403c02a8 - 0x403c02dc
CPU1: Booted secondary processor
CPU1: thread -1, cpu 1, socket 0, mpidr 80000001
Brought up 2 CPUs
SMP: Total of 2 processors activated (3188.32 BogoMIPS).
NET: Registered protocol family 16
11930:22:53 [Klogctl][Info] [(1086)LogCtlInit] LogCtlInit begin
11930:22:53 [Klogctl][Info] [(896)AddLogOutModule] AddLogOutModule:OutputMode=0X00000200,ptLogProcSet=c6031ab0
L310 cache controller enabled
l2x0: 16 ways, CACHE_ID 0x410000c8, AUX_CTRL 0x42450001, Cache size: 524288 B
product_vid = 25
current_board=c0584be8
bootsel=3
bio: create slab <bio-0> at 0
vgaarb: loaded
SCSI subsystem initialized
usbcore: registered new interface driver usbfs
usbcore: registered new interface driver hub
usbcore: registered new device driver usb
Switching to clocksource zx_timer0
NET: Registered protocol family 2
IP route cache hash table entries: 1024 (order: 0, 4096 bytes)
TCP established hash table entries: 4096 (order: 3, 32768 bytes)
TCP bind hash table entries: 4096 (order: 3, 32768 bytes)
TCP: Hash tables configured (established 4096 bind 4096)
TCP: reno registered
UDP hash table entries: 128 (order: 0, 4096 bytes)
UDP-Lite hash table entries: 128 (order: 0, 4096 bytes)
NET: Registered protocol family 1
synopsys pcie probe enter!!!!!!
pcie0 irq is 73
pcie1 irq is 96
synopsys pcie0 controller setting
synopsys pcie0 controller waitting L0 state
synopsys pcie1 controller setting
synopsys pcie1 controller waitting L0 state
PCI host bridge to bus 0000:00
pci_bus 0000:00: root bus resource [mem 0x10000000-0x17ffffff]
PCI: bus0: Fast back to back transfers enabled
PCI host bridge to bus 0000:01
pci_bus 0000:01: root bus resource [mem 0x20000000-0x27ffffff]
PCI: bus1: Fast back to back transfers enabled
tdm registered!
zx_tdm2.0_probe version_20170119
g_tdm_buf =ffdfe000,461fa000
remap tdm reg 9a107000 to f0807000
tdm irq=54
reg 0xf0800028 value is 0x13
tdm binding cpu1....
pon init
ZX_PA_BUF_BASE0=46700000
ZX_VA_BUF_BASE0=c6700000
ZX_ACL_BASE=46720000
ZX_FLOW_BASE=46b20000
ZX_BP_BUFFER_BASE=46ba0000
ZX_DESC_BASE=47ea0000
ZX_TX_UP_DESC_BASE=47f60000
ZX_TX_DN_DESC_BASE=47f70000
ZX_VA_BPPE_BASE=c6700000
ZX_VA_BP_BUF_BASE=c6ba0000
ZX_VA_DESC_BASE=c7ea0000
ZX_VA_TX_UP_DESC_BASE=c7f60000
ZX_VA_TX_DN_DESC_BASE=c7f70000
UNCACHE_ADDR_OFFSET=2a900000
BPPE_POOL_SIZE=2000
NORMAL_BP_BUFFER_SIZE=1200000
JUMBO_BP_SIZE=2800
JUMBO_BPPE_POOL_SIZE=66
BP_BUFFER_SIZE=1300000
ponmode = 0
the pon mode is 0
pon clk reset pin mux
pp init
pp net init ok
switch init
idm_desc_init ffdf8000/461c0000
idm net init ok, idm mtu 2304, rx coal 2000, tx_des dpt 512
NTFS driver 2.1.30 [Flags: R/W].
jffs2: version 2.2. (NAND) © 2001-2006 Red Hat, Inc.
fuse init (API version 7.18)
msgmni has been set to 187
io scheduler noop registered
io scheduler deadline registered (default)
ttyS0 at MMIO 0x0 (irq = 42) is a zx29_UART
ZTE-TSP zx29 UART_0 probe OK
ZTE-TSP zx29 UART driver registered
brd: module loaded
loop: module loaded
Generic platform RAM MTD, (c) 2004 Simtec Electronics
zte_spifc_reg:94407000
spifc->io_base :f0707000
NAND device: Manufacturer ID: 0xc8, Chip ID: 0x01 (ESMT SPI NAND F50L1G41LB 128MiB 3,3V)
NAND Chip: oobsize:0x40, pagesize:0x800, blocksize:0x20000, chipsize:0x8000000, ECC capbility is 8 bits, CRC protection is disabled
Scanning device for bad blocks
##########verinfo=U-Boot V7.0.10P2T21 20190223111911 0x1a00000 0x0 0x8f 0x82
##########u32CurrBaseAddress=1a00000,0
##########u32CurrBaseAddress=1a00000,0
kernel=kernel1,1a00000,2000000
size=1fe0000,offset=1a20000
Creating 10 MTD partitions on "ZX27912x-spifc":
0x000000000000-0x000008000000 : "whole flash"
0x000000000000-0x000000200000 : "u-boot"
0x000000200000-0x000000600000 : "others"
0x000000600000-0x000000a00000 : "parameter tags"
0x000000a00000-0x000000e00000 : "wlan"
0x000000e00000-0x000001600000 : "usercfg"
0x000001600000-0x000001a00000 : "middleware"
0x000001a00000-0x000003a00000 : "kernel1"
0x000003a00000-0x000005a00000 : "kernel2"
0x000001a20000-0x000003a00000 : "rootfs"
zx_spi_probe...master->bus_num:0
zx_spi 9a105000.ssp: master is unqueued, this is deprecated
SPI0 probed
****lc add zx279128_probe*****
zx279128-dwc3 9100000.usb: ***lc add**** dwc3->dev.dma_mask = 0xc05e3070
usbcore: registered new interface driver cdc_acm
cdc_acm: USB Abstract Control Model driver for USB modems and ISDN adapters
usbcore: registered new interface driver usblp
Initializing USB Mass Storage driver...
usbcore: registered new interface driver usb-storage
USB Mass Storage support registered.
usbcore: registered new interface driver usbserial
usbcore: registered new interface driver usbserial_generic
USB Serial support registered for generic
usbserial: USB Serial Driver core
usbcore: registered new interface driver ch341
USB Serial support registered for ch341-uart
usbcore: registered new interface driver cp210x
USB Serial support registered for cp210x
usbcore: registered new interface driver ftdi_sio
USB Serial support registered for FTDI USB Serial Device
ftdi_sio: v1.6.0:USB FTDI Serial Converters Driver
usbcore: registered new interface driver option
USB Serial support registered for GSM modem (1-port)
usbcore: registered new interface driver pl2303
USB Serial support registered for pl2303
mousedev: PS/2 mouse device common for all mice
i2c /dev entries driver
I2C probe successed!
I2C probe successed!
zxwdt: cpu1 wdt enable RegValue 6b
<pdt_wdt_init>(570):creat proc files for watchdog!!!
<pdt_wdt_init>(574):Starting Watchdog Timer...
wdt debug: nr_cpu_ids= 2
zxwdt: heartbeat 8 msec, clock 800000000
usbcore: registered new interface driver usbhid
usbhid: USB HID core driver
nf_conntrack version 0.5.0 (1501 buckets, 8192 max)
ip_tables: (C) 2000-2006 Netfilter Core Team
NET: Registered protocol family 10
ip6_tables: (C) 2000-2006 Netfilter Core Team
IPv6 over IPv4 tunneling driver
NET: Registered protocol family 17
Bridge firewalling registered
Ebtables v2.0 registered
PPP generic driver version 2.4.2
NET: Registered protocol family 24
zte--oss cpu usage module init
<LOGID000000005>11930:22:58 [KIGMPSNP][Warn] [br_multicast_se(213)br_del_addr_reg] register gIgmpDelAddrHook succeed!
<LOGID000000005>11930:22:58 [KIGMPSNP][Warn] [br_multicast_se(219)br_del_addr_reg] register gMldDelAddrHook succeed!
fastforward_init start !
fastforwardVFS: Mounted root (jffs2 filesystem) readonly on device 31:9.
Freeing init memory: 152K
init started:  BusyBox v1.01 (2019.02.23-03:08+0000) multi-call binary
Starting pid 427, console /dev/ttyS0: '/etc/init.d/rcS'
======================================================
mounting /dev/mtdblock3 to /tagparam, wait ...
======================================================
Pre-initialization script ...
  Mounting ramdisk at /var
  Mounting /dev/mtdblock5 to /userconfig
  Mount ok!
  Mounting /dev/mtdblock6 to /usr/local/ct
  Mount ok!
======================================================
mounting /dev/mtdblock4 to /wlan, wait ...
======================================================
Configuring MAC interfaces
Bringing up interface lo
Bringing up interface mii0
Set promisc for device mii0
 Configuring with no IP address (i.e. for PPP)
mux[0]=c155ff9
mux[1]=557f575
mux[2]=555aaaa
mux[3]=fc5fff
storage_wakeup_proc_create success!
<verinfo_module_init>(641)---->verinfo=U-Boot V7.0.10P2T21 20190223111911 0x1a00000 0x0 0x8f 0x82
addr==1a00000
<verinfo_module_init>(646)----><verinfo_module_init>(648)----><verinfo_module_init>(650)---->can find /usr/java/osgi_verosgi_version_info_get erro!
GN25L95          found.
register fpga driver success, major=222
= TM Module SYS FS Init ended successfully =
tm_initModule begin...
tm_pp_initial start
[TM][ppglb_set_acl_base]input: base=1181876224
 upa_set_rr_mask_cfg input: upa_rr_mask = 0x2ab
 tm_pp_initial--------finish
tm_switch_initial----start
tm_switch_initial----finish
tm_initial successed !!!
tm_initModule end...
ethdriver_init....
g_mii_dev_name[0]  sw
g_mii_dev_name[1]  pon
zteGpmac_initModule begin...
=== GponMac Supported MaxTcont: 16 MaxPLI: 800B ===
##huoqf zteGponAsicStarttimeChkResultInit write cfg=10
##huoqf zteGponAsicStarttimeChkResultInit read cfg=10
= PON Module Operate ended successfully =
create zteGpon_rei_task ok!
= GMAC Module SYS FS Init ended successfully =
zteGpmac_initModule end...
zx279100_gpon_Init ok
<LOGID000000005>11930:23:03 [KMONITOR][Warn] [monitor.c(585)MontorSendMsg] netlink_unicast failed:msgid = 0xa4a7, ptr =   (null), len = 0
Init switch module
unicnt 4, wancnt 1, wifi cnt 0, all ports 5, portmask 0x0000002f
 switch config GPON SFU mode!
-------chip_tm_init end-----
[SW]set cpu queue rate limit to 8000pps
zte_api_sw_port_set_port_ratelimit port:(6) direct:(1) enable:(1) rate:(2048 kpbs) ifgMode:(1)
zte_api_sw_port_set_port_ratelimit port:(7) direct:(1) enable:(1) rate:(2048 kpbs) ifgMode:(1)
Init switch module Success
GN25L95          found.
bsp_i2c_probe 0x50 success!
vendor name = ZTE_B+_G
 optical PN(0x60) =
 optical PN(0x28) = GN25L95
udpwatchd inited!
kudp  inited!
Init codec v2.2(2017-12-19)!
----VoIPCodecInit ch0
----VoIPCodecInit ch1
P_2833: Setup 0
DSP device setup OK!
insmod: cannot open module `/kmodule/redirusb.ko': No such file or directory
===================================================================
region code:7
region name:EngLand
USER_CFG is same as ETC_CFG, donot need copy
===================================================================
  Database default setting is [current : 7]
cp: /etc/gateinfoSCPD.xml: No such file or directory
cp: /etc/gateconnSCPD.xml: No such file or directory
Starting pid 624, console /dev/ttyS0: '/sbin/getty'
11930:23:04 [OSS_pc][Error] [pc.c(1978)main]  Could not set affinity

F620
11930:23:07 [dhcp4c][Warn] [dhcp4c_inst.c(3946)_dhcp4cRegSendO] Send code[60]fun[0x1807a4] is replaced by fun[0x1851f0]
11930:23:07 [OSS_cspd][Error] [oss_comm.c(2087)SocketAsynSendM] sender = 0x00010000 ,reciver = 0x00020101 , Event = 0xa4a7
11930:23:07 [OSS_cspd][Error] [oss_comm.c(2089)SocketAsynSendM] send ilen = -1 Len = 32  errno = 2
11930:23:07 [OSS_cspd][Error] [oss_common.c(480)ASEND] [][00010000] Send task Message[0XA4A7] to [00020101] in SocketAsynSendMsg()  ERROR !
11930:23:07 [DB][Warn] [dbc_def_dev_inf(324)dbGetOnuMode] boardType : F620
11930:23:07 [DB][Warn] [dbc_def_dev_inf(430)dbPersonInitVer] get parameter from Flash failed!VersionMode
11930:23:07 [DB][Warn] [dbc_mgr_tbl.c(1562)dbSetValComm] not find domain table(DevInfo) domain(VersionMode)
11930:23:07 [DB][Error] [dbc_mgr_def.c(75)dbMgrStaticSetI] not find table (WLANCountry)
11930:23:07 [DB][Error] [dbc_mgr_def.c(75)dbMgrStaticSetI] not find table (PDTWLANWAPI)
11930:23:07 [DB][Error] [dbc_def_gponcfg(105)dbDefGPONCFG] get RegisterID  from flash failed !
11930:23:07 [DB][Error] [dbc_def_gponcfg(132)dbDefGPONCFG] get Loid from flash failed !
11930:23:07 [DB][Error] [dbc_def_gponcfg(143)dbDefGPONCFG] get LoidPwd  from flash failed !
11930:23:07 [DB][Warn] [dbc_person_dev_(201)dbPersonInitHVT] get parameter from Flash failed!HardwareVerTag
11930:23:07 [DB][Warn] [dbc_person_auth(47)dbPersonInitAut] get parameter from Flash failed!Adminname
11930:23:07 [DB][Warn] [dbc_person_auth(62)dbPersonInitAut] get parameter from Flash failed!Username
11930:23:07 [DB][Warn] [dbc_person_auth(99)dbPersonInitAut] get parameter from Flash failed!admin's Password
11930:23:07 [DB][Warn] [dbc_person_auth(114)dbPersonInitAut] get parameter from Flash failed!user's Password
11930:23:08 [OSS_pc][Warn] [pc.c(1071)StartProgram] pName(mount) is not ProcName(iptables),startMode=0x0000,fpid=65794,Starter(firewall),cmd(*****)
11930:23:08 [OSS_pc][Warn] [pc.c(1071)StartProgram] pName(iptables) is not ProcName(ip6tables),startMode=0x0000,fpid=65794,Starter(firewall),cmd(*)
11930:23:08 [OSS_pc][Warn] [pc.c(1071)StartProgram] pName(iptables) is not ProcName(ip6tables),startMode=0x0000,fpid=65794,Starter(firewall),cmd(*)
11930:23:08 [OSS_pc][Warn] [pc.c(1071)StartProgram] pName(iptables) is not ProcName(ip6tables),startMode=0x0000,fpid=65794,Starter(firewall),cmd(*)
11930:23:08 [OSS_pc][Warn] [pc.c(1071)StartProgram] pName(iptables) is not ProcName(ip6tables),startMode=0x0000,fpid=65794,Starter(firewall),cmd(*)
11930:23:09 [upgrade_mgr][Error] [upgrade_mgr.c(2464)UpgradeInit] =====RegionCodeForTools=-14=====
11930:23:09 [dss][Warn] [dss_lla.c(972)DssLlaMain] The Dss' lpMsg is null.
11930:23:09 [bsp_mgr][Error] [bsp_mgr.c(158)BspMgrInit] BspMgr INIT_SUCCESS
11930:23:10 [DB][Crit] [dbc_core.c(462)dbPersonInitPro] VIP_VOIP: Set VoIP Protocol SIP
11930:23:10 [DB][Error] [dbc_def_timepol(217)dbWlanTimeTrans] {dbWlanTimeTrans} find:[0], [-1]:[-1]
11930:23:10 [DB][Error] [dbc_core_compat(900)dbUserInfoTrans] not find table
11930:23:10 [DB][Warn] [dbc_pdt_transfe(500)bIsNeedUpInc] ==== bIsNeedUpInc: [regcode:7]V7.0.10P2T2########br's FDB_MAX[1024]
0--->V7.0.10P2T2ADDRCONF(NETDEV_UP): br0: link is not ready
0
11930:23:10 [DB][Warn] [dbc_core.c(2603)dbAdaptDataByOn] enter dbAdaptDataByOnuMode
br0: using kernel STP
11930:23:10 [OSS_cspd][Warn] [oss_sche.c(819)RunProcess] RunProcess process[DB] Event[0x1100] dwUsedTicks[290]
                                                                                                              ------------------------------------)
11930:23:10 [log_mgr][Emerg] [log_mgr.c(944)logSetSaveEnabl] Log configure change:[LogFunction] Log SaveFile Service Stop Success!
11930:23:10 [log_mgr][Emerg] [log_mgr.c(1009)logSetSaveLevel] Log configure change:[LogFunction] Log SaveFile LogLevel is Set 4!
11930:23:10 [dhcp6s][Warn] [dhcp6s_main.c(1898)getHwMacByIfNam] Ioctl failed!
11930:23:10 [dhcp6s][Error] [dhcp6s_main.c(1985)_DHCP6SCreateSo] invalid interface
ethdrv_dev_ioctl  ,brdev_set.port_id 0 ,brdev_set.name eth0 ,brdev_set.flag 0
11930:23:10 [dhcp6s][Warn] [dhcp6s_main.c(2276)startDhcp6sInst] startDhcp6sInst, create socket failed
11930:23:10 [usb_stor][Error] [usbbakrst_cmapi(536)CmUsbBakRstSynD] BakFile Name Error(usbbak.cfg)
                                                                                                  ethdrv_dev_ioctl  ,brdev_set.port_id 1 ,brdev_se
ethdrv_dev_ioctl  ,brdev_set.port_id 2 ,brdev_set.name eth2 ,brdev_set.flag 0
ethdrv_dev_ioctl  ,brdev_set.port_id 3 ,brdev_set.name eth3 ,brdev_set.flag 0
=== GponMac Supported MaxTcont: 16 MaxPLI: 800B ===
[sw_port_set_port_floodcontrol] not support now!
[sw_port_set_port_floodcontrol] not support now!
[sw_port_set_port_floodcontrol] not support now!
[sw_port_set_port_floodcontrol] not support now!
[sw_port_set_port_floodcontrol] not support now!
[sw_port_set_port_floodcontrol] not support now!
[sw_port_set_port_floodcontrol] not support now!
[sw_port_set_port_floodcontrol] not support now!
sw_port_set_port_multicastrate not support now!
zte_api_sw_port_set_port_broadcastrate port:(0) direct:(0) enable:(0) rate:(1024000 kpbs) ifgMode:(1)
sw_port_set_port_multicastrate not support now!
zte_api_sw_port_set_port_broadcastrate port:(1) direct:(0) enable:(0) rate:(1024000 kpbs) ifgMode:(1)
sw_port_set_port_multicastrate not support now!
zte_api_sw_port_set_port_broadcastrate port:(2) direct:(0) enable:(0) rate:(1024000 kpbs) ifgMode:(1)
sw_port_set_port_multicastrate not support now!
zte_api_sw_port_set_port_broadcastrate port:(3) direct:(0) enable:(0) rate:(1024000 kpbs) ifgMode:(1)
zte_api_sw_port_set_port_ratelimit port:(0) direct:(0) enable:(0) rate:(1000000 kpbs) ifgMode:(1)
zte_api_sw_port_set_port_ratelimit port:(0) direct:(1) enable:(0) rate:(1000000 kpbs) ifgMode:(1)
zte_api_sw_port_set_port_ratelimit port:(1) direct:(0) enable:(0) rate:(1000000 kpbs) ifgMode:(1)
zte_api_sw_port_set_port_ratelimit port:(1) direct:(1) enable:(0) rate:(1000000 kpbs) ifgMode:(1)
zte_api_sw_port_set_port_ratelimit port:(2) direct:(0) enable:(0) rate:(1000000 kpbs) ifgMode:(1)
zte_api_sw_port_set_port_ratelimit port:(2) direct:(1) enable:(0) rate:(1000000 kpbs) ifgMode:(1)
zte_api_sw_port_set_port_ratelimit port:(3) direct:(0) enable:(0) rate:(1000000 kpbs) ifgMode:(1)
zte_api_sw_port_set_port_ratelimit port:(3) direct:(1) enable:(0) rate:(1000000 kpbs) ifgMode:(1)
11930:23:11 [usb_mgr][Error] [usb_mgr_product(227)CspUsbMgrProduc] do not have usb port
                                                                                       g_iUpLinkType=4
11930:23:11 [OSS_pc][Warn] [pc.c(1071)StartProgram] pName(iptables) is not ProcName(ip6tables),startMode=0x0000,fpid=65794,Starter(firewall),cmd(*)
11930:23:12 [OSS_pc][Warn] [pc.c(1071)StartProgram] pName(ip6tables) is not ProcName(),startMode=0x0000,fpid=65794,Starter(firewall),cmd(*****)
11930:23:12 [OSS_pc][Warn] [pc.c(1071)StartProgram] pName(ip6tables) is not ProcName(),startMode=0x0000,fpid=65794,Starter(firewall),cmd(*****)
11930:23:12 [OSS_pc][Warn] [pc.c(1071)StartProgram] pName(ip6tables) is not ProcName(),startMode=0x0000,fpid=65794,Starter(firewall),cmd(*****)
11930:23:12 [OSS_pc][Warn] [pc.c(1071)StartProgram] pName(ip6tables) is not ProcName(),startMode=0x0000,fpid=65794,Starter(firewall),cmd(*****)
                                                                                                                                               sip!
ftp alg change port ok!
rtsp alg change port ok!
11930:23:12 [OSS_pc][Warn] [pc.c(1071)StartProgram] pName(create) is not ProcName(ebtables),startMode=0x0000,fpid=65794,Starter(firewall),cmd(****)
11930:23:12 [OSS_pc][Warn] [pc.c(1071)StartProgram] pName(mount) is not ProcName(ebtables),startMode=0x0000,fpid=65794,Starter(firewall),cmd(*****)
11930:23:12 [dns_mgr][Warn] [ifs_api.c(2648)GetRouteIFInfo] parameter is illegal![IGD.WD1.WCD1.WCPPP1]
11930:23:12 [igmpproxy_mgr][Warn] [ifs_api.c(2648)GetRouteIFInfo] parameter is illegal![IGD.WD1.WCD1.WCPPP1]
11930:23:12 [ddns_mgr][Warn] [ddns_mgr.c(1400)ddnsAddClientLi] call dbAPIQryView failed!DBVIEW_DDNS_SERVICE,name
11930:23:12 [ddns_mgr][Warn] [ddns_mgr.c(1319)ddnsInitClientL] Call function failed!ddnsAddClientListNode
11930:23:12 [dss][Warn] [dss_lla.c(972)DssLlaMain] The Dss' lpMsg is null.
11930:23:12 [prefix_mgr][Error] [prefix_mgr.c(2865)PrefixMgrInit] Init Pvendor name = ZTE_B+_G refix Lock error!
11930:23:12 [
 optical PN(0x60) =
pon_dev_mgr][Error] [pon_dev_mgr optical PN(0x28) = GN25L95
.c(425)get_falsify_def] call  GetTagParam failed!!!!
11930:23:12 [pon_dev_mgr][Error] [pon_dev_mgr.c(1065)FalsfyDefInitVi] call get_falsify_defend_mode failed! iRet = -7
                                                                                                                    >>>>>>>>>>>>>>>>>>>>>>>>gpon_o<
11930:23:12 [por<LOGID000000005>11930:23:12 [KPORTLOCATE][Warn] [br_portlocate.c(2414)set_portlocate_] pppoe portlocate vendorInfo is:00000DE9
<LOGID000000005>11930:23:12 [KPORTLOCATE][Warn] [br_portlocate.c(2422)set_portlocate_] CharToHex ok,g_pppoe_vendorInfo:e90d0000!
tLocate_mgr][Warn] [portLocate_mgr.(250)portLocateStart] portLocateInit begin set format,portLocateSetPPPoEVendorInfo:00000DE9
                                                                                                                              device eth0 entered e
device eth1 entered promiscuous mode
device eth2 entered promiscuous mode
device eth3 entered promiscuous mode
====================gpon_omci start======================
##O7 STATE 0##!
11930:23:13 [ifs_mgr][Warn] [ifs_notifier.c(377)delRegNotifier] paramete<LOGID000000005>11930:23:13 [KIGMPSNP][Error] [br_multicast_se(1062)set_tr!
r is illegal!not found, pid[65810]
1193<LOGID000000005>11930:23:13 [KIGMPSNP][Error] [br_multicast_se(1062)set_trap_unknow] port1 trap_unknow_report_en is 0!
0:23:13 [ifs_mgr][Warn] [ifs_not<LOGID000000005>11930:23:13 [KIGMPSNP][Error] [br_multicast_se(1062)set_trap_unknow] port2 trap_unknow_report_en i!
ifier.c(377)delRegNotifier] parameter is<LOGID000000005>11930:23:13 [KIGMPSNP][Error] [br_multicast_se(1062)set_trap_unknow] port3 trap_unknow_rep!
 illegal!not found, pid[65850]
11930:23:13 [igmpproxy_mgr][Warn] [ifs_api.c(2648)GetRouteIFInfo] parameter is illegal![IGD.WD1.WCD1.WCPPP1]
                                                                                                            voip main binding cpu_mask 0x2....
Process_Perf's Event(4352) is not support !!
==========================sys process start=========================
=====================omci sender process start=====================
Omci get Byte Order is Little-Endian
g_bByteSort(0)
=========================omci process start=========================
OA_Sysdrv_GetTcontBufferSize: value(0) is out of range, use def value:256
Omci Debug:CmWLANListConfig.dwCount = 4
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN1]
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(334)defCommand] defCommand,IGD.LD1.WLAN1
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsg] vlanRuleSetMsg:Command failed!
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN1]
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(334)defCommand] defCommand,IGD.LD1.WLAN1
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsmac 0 phy status changed: 1000M full-duplex
g] vlanRuleSetMsg:Command failed!
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN1]
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(555)untagCommand] untagCommand,IGD.LD1.WLAN1
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsg] vlanRuleSetMsg:Command failed!
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN1]
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(555)untagCommand] untagCommand,IGD.LD1.WLAN1
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsg] vlanRuleSetMsg:Command failed!
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN2]
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(334)defCommand] defCommand,IGD.LD1.WLAN2
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsg] vlanRuleSetMsg:Command failed!
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN2]
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(334)defCommand] defCommand,IGD.LD1.WLAN2
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsg] vlanRuleSetMsg:Command failed!
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN2]
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(555)untagCommand] untagCommand,IGD.LD1.WLAN2
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsg] vlanRuleSetMsg:Command failed!
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN2]
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(555)untagCommand] untagCommand,IGD.LD1.WLAN2
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsg] vlanRuleSetMsg:Command failed!
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN3]
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(334)defCommand] defCommand,IGD.LD1.WLAN3
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsg] vlanRuleSetMsg:Command failed!
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN3]
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(334)defCommand] defCommand,IGD.LD1.WLAN3
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsg] vlanRuleSetMsg:Command failed!
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN3]
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(555)untagCommand] untagCommand,IGD.LD1.WLAN3
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsg] vlanRuleSetMsg:Command failed!
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN3]
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(555)untagCommand] untagCommand,IGD.LD1.WLAN3
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsg] vlanRuleSetMsg:Command failed!
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN4]
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(334)defCommand] defCommand,IGD.LD1.WLAN4
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsg] vlanRuleSetMsg:Command failed!
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN4]
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(334)defCommand] defCommand,IGD.LD1.WLAN4
11930:23:14 [tr069][Warn] [trparameter.c(3501)Tr069GetTreePat] Load universal data XML:/etc/device_data.xml
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsg] vlanRuleSetMsg:Command failed!
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN4]
11930:23:14 [vlan_mobr0: topology change detected, propagating
br0: port 1(eth0) entered forwarding state
br0: port 1(eth0) entered forwarding state
dule_mgr][Error] [vlan_module_mgr(555)untagCommand] untagCommand,IGD.LD1.WLAN4
11930:23ADDRCONF(NETDEV_CHANGE): br0: link becomes ready
:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsg] vlanRuleSetMsg:Command failed!
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN4]
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(555)untagCommand] untagCommand,IGD.LD1.WLAN4
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsg] vlanRuleSetMsg:Command failed!
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN5]
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(334)defCommand] defCommand,IGD.LD1.WLAN5
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsg] vlanRuleSetMsg:Command failed!
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN5]
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(334)defCommand] defCommand,IGD.LD1.WLAN5
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsg] vlanRuleSetMsg:Command failed!
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN5]
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(555)untagCommand] untagCommand,IGD.LD1.WLAN5
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsg] vlanRuleSetMsg:Command failed!
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN5]
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(555)untagCommand] untagCommand,IGD.LD1.WLAN5
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsg] vlanRuleSetMsg:Command failed!
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN6]
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(334)defCommand] defCommand,IGD.LD1.WLAN6
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsg] vlanRuleSetMsg:Command failed!
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN6]
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(334)defCommand] defCommand,IGD.LD1.WLAN6
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsg] vlanRuleSetMsg:Command failed!
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN6]
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(555)untagCommand] untagCommand,IGD.LD1.WLAN6
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsg] vlanRuleSetMsg:Command failed!
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN6]
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(555)untagCommand] untagCommand,IGD.LD1.WLAN6
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsg] vlanRuleSetMsg:Command failed!
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN7]
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(334)defCommand] defCommand,IGD.LD1.WLAN7
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsg] vlanRuleSetMsg:Command failed!
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN7]
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(334)defCommand] defCommand,IGD.LD1.WLAN7
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsg] vlanRuleSetMsg:Command failed!
11930:23:14 [U_dnsmasq][Error] [dnsmasq.c(511)main] |dnsmasq| bind interface socket failed 99
11930:23:14 [U_dnsmasq][Error] [dnsmasq.c(541)main] |dnsmasq| tcp, bind interface socket failed,tcpfd:5, error=99, errstr=Cannot assign requested s
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN7]
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(555)untagCommand] untagCommand,IGD.LD1.WLAN7
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsg] vlanRuleSetMsg:Command failed!
                                                                                                         VOP_DspTraceTaskEntery entered:POWER ON!!0
                                                                                                                                                  0
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN7]
                                                                                                         VOP_TaskEntry entered:POWER ON!!!wState:0
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(555)untagCommand] untagCommand,IGD.LD1.WLAN7
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsg] vlanRuleSetMsg:Command failed!
11930:23:14 [BCC][Warn] [bcc_entry.c(242)BCC_TaskEntry] Unknown Event=0x00001100 when BCC PowerOn!
11930:23:14 [upnp_igd][Warn] [upnpigd.c(324)UPnPIGDProcessR] parameter is invalid!tWanName
11930:23:14 [tr069][Warn] [trparameter.c(3524)Tr069GetTreePat] Load universal services XML:/etc/device_sip.xml
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN8]
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(334)defCommand] defCommand,IGD.LD1.WLAN8
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsg] vlanRuleSetMsg:Command failed!
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN8]
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(334)defCommand] defCommand,IGD.LD1.WLAN8
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsg] vlanRuleSetMsg:Command failed!
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN8]
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(555)untagCommand] untagCommand,IGD.LD1.WLAN8
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsg] vlanRuleSetMsg:Command failed!
11930:23:14 [vlan_module_mgr][Warn] [ifs_api.c(1788)getIFBaseConfig] Call function failed![IGD.LD1.WLAN8]
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(555)untagCommand] untagCommand,IGD.LD1.WLAN8
11930:23:14 [vlan_module_mgr][Error] [vlan_module_mgr(925)vlanRuleSetMsg] vlanRuleSetMsg:Command failed!
                                                                                                          g_MeCtr_Configure=0x00000000,g_MeCtr_Cre0
OA_Pondrv_GetTcontMax result:0 tcontmax:8
OA_Pondrv_GetTcontQueueMax result:0 tcontqueuemax:8
[GoldenSea]TcontID[1], policy:0, pqinfo:0
[GoldenSea]TcontID[2], policy:0, pqinfo:0
[GoldenSea]TcontID[3], policy:0, pqinfo:0
[GoldenSea]TcontID[4], policy:0, pqinfo:0
[GoldenSea]TcontID[5], policy:0, pqinfo:0
[GoldenSea]TcontID[6], policy:0, pqinfo:0
[GoldenSea]TcontID[7], policy:0, pqinfo:0
[GoldenSea]TcontID[8], policy:0, pqinfo:0
[FWPM]pInstList.dwCount = 0
[FWIP]pInstList.dwCount = 0
[FWSC]pInstList.dwCount = 0

DB INIT not support this MECLASS[350]
##Exception! Regist me class:350 DB failed! ret:10##-zhangyc
[OA_Mng_Event_Cfg] Event (0x0500000c) no found!
[OA_Chip_Mng_Event_CallBack]Call pFucMngExec ucRet=2
11930:23:14 [omci][Error] [pon_dev_cmapi.c(316)CmPonGetIspCode] 04##################call  GetTagParam failed!!!!##################
                                                                                                                                  call CmPonGetIsp7
[OA_Chip_Mng_Event_CallBack]Call pFucMngExec ucRet=1
11930:23:14 [omci][Error] [pon_dev_cmapi.c(365)CmFalsifyGetPdt] ##################call  Get TAG_ID_PRODUCTION_SN failed!!!!##################
                                                                                                                                             call 7
[OA_Chip_Mng_Event_CallBack]Call pFucMngExec ucRet=1
Open /proc/capability/battery fail
11930:23:14 [omci][Error] [pon_baseinfo_cm(516)cmGetUPSInfo] cmGetUPSInfo: Get upsOnline error!
                                                                                               Call cmGPonGetUPSInfo error, iRet = -257
[OA_Chip_Mng_Event_CallBack]Call pFucMngExec [ADAPTER]set gpon up!!!
====EVENT_O7_STATE_SAVE OFF====
DEbug: GPON PIN_MUX_REG3:(0xdc1fff)
ucRet=255
GetEnvPara_noproc /userconfig/env_param
                                       GetEnvPara_noproc /userconfig/env_param
                                                                              GetEnvPara_noproc /userconfig/env_param
                                                                                                                     GetEnvPara_noproc /userconfigm
11930:23:15 [tr069][Warn] [srm_cmapi.c(456)CmSrmGetCpuInfo] CmSendMsg2MM return error!
11930:23:15 [tr069][Error] [notify_value_ch(572)NotifyListAdd] Get param value error !
11930:23:15 [tr069][Warn] [srm_cmapi.c(456)CmSrmGetCpuInfo] CmSendMsg2MM return error!
11930:23:15 [tr069][Error] [notify_value_ch(572)NotifyListAdd] Get param value error !
11930:23:15 [omci][Error] [pon_upgrade_cma(275)CmGetPrivatePro] CmGetPrivateProfileInt: GetPrivateProfileInt FAILURE!
                                                                                                                      Call CmGetPrivateProfileInt g
[OA_Chip_Mng_Event_CallBack]Call pFucMngExec ucRet=1
power status is 0x0!!!
[LHP]Update loid_authencation state wResult 0 G_ONU_REG_Authenstates 0
[OA_Mng_Event_Cfg] Event (0x05010028) no found!
[OA_Chip_Mng_Event_CallBack]Call pFucMngExec ucRet=2
##Get management vlan about HG failed!##-zhangyc
[OA_Mng_Event_Cfg] Event (0x05010029) no found!
[OA_Chip_Mng_Event_CallBack]Call pFucMngExec ucRet=2
[OA_Mng_Event_Cfg] Event (0x05010029) no found!
[OA_Chip_Mng_Event_CallBack]Call pFucMngExec ucRet=2
[OA_Mng_Event_Cfg] Event (0x05010029) no found!
[OA_Chip_Mng_Event_CallBack]Call pFucMngExec ucRet=2
[OA_Mng_Event_Cfg] Event (0x05010029) no found!
[OA_Chip_Mng_Event_CallBack]Call pFucMngExec ucRet=2
step into Clear_All_Dot1ag_MA
step into Clear_All_Dot1ag_MD

[alecal]ZTE----pon link activate success!
##O7 STATE 0##!
               Process_Perf's Event(4355) is not support !!
not support alarm event 0x1103.
[LHP]Update loid_authencation state wResult 0 G_ONU_REG_Authenstates 0
[LHP]Update loid_authencation state wResult 0 G_ONU_REG_Authenstates 0
[LHP]Update loid_authencation state wResult 0 G_ONU_REG_Authenstates 0
[LHP]Update loid_authencation state wResult 0 G_ONU_REG_Authenstates 0
-----VOP_TaskEntopen DSP_dev driver!
open DSP_TRACE driver!
ry entered:DSP START WORK!!!-------wState:1
                                           UDP MOD START
ch:0 pcm mode:G711A_U
ch 0 set pcm type is ok,val is 0!
ch:1 pcm mode:G711A_U
ch 1 set pcm type is ok,val is 0!
Board default NO PTC
slc zarlink binding cpu1....
Board default NO PTC
Board default NO PTC
Board default NO PTC
SLC:User SLIC Driver V3.0.0 Init Finish.
usrline_ioctl port:0 is disable now!
port:0 DcIndex:1-1 U:52 A:24 RingIndex:2 VPK:70 100msEn:0, impeIndex:2 ePTC:0 dwImpe:600 rxgain(D-A):-8, txgain(A-D):0, pcmlaw:0
usrline_ioctl port:1 is disable now!
port:1 DcIndex:1-1 U:52 A:24 RingIndex:2 VPK:70 100msEn:0, impeIndex:2 ePTC:0 dwImpe:600 rxgain(D-A):-8, txgain(A-D):0, pcmlaw:0
Find line 0 chan 1, cs 1
Find line 1 chan 0, cs 1
cann't Find a line  2
cann't Find a line  3
legerity_init dev:1 cs:1.
rcn:0x8 pcn:0x75
9642 found.
VpMakeDeviceObject dev:1.
===LE9642:VP_DEV_886_SERIES dev ac dc ring parameters config!!!bPort:1===
VpMakeLineObject dev:1 line:0.
===LE9642:VP_DEV_886_SERIES dev ac dc ring parameters config!!!bPort:0===
VpMakeLineObject dev:1 line:1.
VpInitDevice dev:1.
Register port 1
Register port 0
wait for CHIP_INITED, total:20 now:0 times 500ms
wait for CHIP_INITED, total:20 now:1 times 500ms
eventCategory:0x0002, eventId:0x0400, channelId:0x0000, lineId:0x00c5, deviceId:0x0001
VP_EVCAT_RESPONSE : eventId 0x0400
VpInitLine line:0 on dev:1 for port:1.
VpInitLine line:1 on dev:1 for port:0.
wait for PORT_INITED, total:20 now:0 times 10ms
eventCategory:0x0002, eventId:0x0800, channelId:0x0000, lineId:0x0001, deviceId:0x0001
VP_EVCAT_RESPONSE : eventId 0x0800
eventCategory:0x0002, eventId:0x0800, channelId:0x0001, lineId:0x0000, deviceId:0x0001
VP_EVCAT_RESPONSE : eventId 0x0800
VpCalLine line:0 on dev:1 for port:1
VpCalLine line:1 on dev:1 for port:0
wait for PORT_CAL_CMP, total:20 now:0 times 500ms
wait for PORT_CAL_CMP, total:20 now:1 times 500ms
eventCategory:0x0002, eventId:0x0040, channelId:0x0000, lineId:0x0001, deviceId:0x0001
VP_EVCAT_RESPONSE : eventId 0x0040
eventCategory:0x0002, eventId:0x0040, channelId:0x0001, lineId:0x0000, deviceId:0x0001
VP_EVCAT_RESPONSE : eventId 0x0040
line:0 on dev:1 for port:1 init OK!
line:1 on dev:1 for port:0 init OK!
set dev:1 power limit:9945mW
dev:1 cs:1 init OK.
The legerity init is finished.
11930:23:29 [upgrade_mgr][Error] [upgrade_mgr.c(3191)upgradeProcTime] time is 36!
11930:23:29 [upgrade_mgr][Error] [upgrade_mgr.c(3209)upgradeProcTime] tagparam file same, no need copy!
11930:23:32 [pon_dev_mgr][Error] [pon_dev_mgr.c(425)get_falsify_def] call  GetTagParam failed!!!!
11930:23:32 [pon_dev_mgr][Error] [pon_dev_mgr.c(1030)FalsfyDefInit] call get_falsify_defend_mode failed! iRet = -7

F620
Login: zte_api_sw_port_set_port_ratelimit port:(6) direct:(1) enable:(0) rate:(0 kpbs) ifgMode:(1)
zte_api_sw_port_set_port_ratelimit port:(7) direct:(1) enable:(0) rate:(0 kpbs) ifgMode:(1)
```

