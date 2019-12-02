﻿D-Link DIR-505路由器刷OpenWrt固件翻墙教程
=====================================

前面的教程用结合 TP-LINK TL-WR2543N 来讲解翻墙原理与方法，并不是我特别推荐TP-LINK TL-WR2543N，而是因为手头正好有这个路由器。毫无疑问，初学者使用教程同款路由器比较容易上手。但此型号趋向退市，价格也不便宜，网上有二手货，如果功能正常倒也可以考虑

另外的选择，是使用 D-Link DIR-505 便携式路由器。配置高，价格便宜

D-Link DIR 505 硬件信息
--------

    Architecture:    MIPS 24Kc
    Vendor:          Atheros
    Bootloader:      UBoot 1.1.4
    System-On-Chip:  SoC: Atheros AR9330 rev 1
    CPU/Speed:       Atheros AR9330 400.000MHz
    Flash-Chip:      NANYA NT5TU32M16DG-AC
    Flash size:      8192 KiB
    RAM:             64 MiB
    Wireless:        802.11b/g/n
    Ethernet:        10/100 full duplex
    USB:             Yes 1 x 2.0 ar7240-ehci
    Serial:          Yes - tested working over TTL converter (3.3V!)
    JTAG:            Nope

与之同价格档次的TP-LINK TL-WR706N 150M迷你型无线路由器 AR9331 SOC 2MB Flash/16MB RAM 相比之下简直是垃圾。我花数百元购买的TP-LINK TL-WR2543N，也不过是8MB Flash, 64MB RAM内存

还有，D-Link DIR-505 自带不死恢复模式，调试OpenWrt系统出现问题时我们既可以进 D-Link 的恢复模式刷新固件，也可以进入 OpenWrt 的恢复模式刷新固件，可谓是最安全的路由器

如何购买 D-Link DIR 505 A1
--------

我不是D-Link的员工，也无意为其做广告。DIR-505是我购买的第一款D-Link路由器

我是2014年8月从淘宝 D-Link官方旗舰店买的 D-Link DIR 505 A1，69元, 固件版本号：1.03CN。买了后，看了下手机淘宝，只要59元。准备再入一个，都刷上 OpenWrt，方便随时随地无障碍上网

---

**最简单的路由器刷OpenWrt翻墙方案:**

- [https://github.com/softwaredownload/openwrt-fanqiang](https://github.com/softwaredownload/openwrt-fanqiang "最简单的路由器刷OpenWrt固件翻墙教程")

**在线阅读OpenWrt路由器翻墙、科学上网器教程:**

- [https://fanqiang.software-download.name](https://fanqiang.software-download.name)
- [https://github.com/softwaredownload/openwrt-fanqiang/blob/master/SUMMARY.md](https://github.com/softwaredownload/openwrt-fanqiang/blob/master/SUMMARY.md)
