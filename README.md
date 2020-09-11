# MSI-MAG-Z490-TOMAHAWK-i7-10700k-OpenCore

MSI MAG Z490 TOMAHAWK i7 10700k 成功安装MacOS Catalina 10.15.6。

主板信息：<a href="https://www.msi.com/Motherboard/MAG-Z490-TOMAHAWK/Specification" >MSI -></a>

**引导程序: OpenCore 0.6.1**

# 硬件

- CPU：Intel I7 10700k
- 主板：MSI MAG Z490 TOMAHAWK
- 声卡：ALCS1200A，官方资料为 Realtek ALC1200-VD1，ubuntu 提取显示为 Realtek ALCS1200A
- 网卡：1x Realtek® RTL8125B 2.5G LAN + 1x Intel I219V 1G LAN
- 无线网卡：fenvi FV-T919（BCM94360CD）
- 内存：32GB DDR4 3200MHz
- 显卡：蓝宝石 Radeon RX 590 8GB 超白金极光特别版（12nm满血版）

# 正常

- [x] **ALCS1200A**：自编 AppleALC.kext, layout-id=11（已提交AppleALC.kext)
- [x] **USB**：USBInjectAll.kext
- [x] **UHD630（无头模式）**
- [x] **RX 590 8G**
- [x] **iMessage/FaceTime**
- [x] **睡眠/唤醒**

# 注意

如果没有独显，请修改配置文件中的核显信息和驱动
