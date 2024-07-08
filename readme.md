## Dell Vostro 3681 Small Desktop 黑苹果 OpenCore EFI

- 公司配的测试机器

### 可完美运行

- macOS Sonoma 14.5

### OpenCore

[OpenCore 1.0.0](https://github.com/acidanthera/OpenCorePkg)

### 机器配置

- BIOS: 2.5.1
- 主板: 戴尔 B460
- 处理器: Intel 10代 i3-10100
- 内存: 镁光 8GB DDR4 2666 Mhz
- 显卡: 英特尔® 超核芯显卡 630
- 声卡: Realtek ALC3246
- 硬盘: 机械硬盘1TB
- 网卡: Realtek RTL8111H
- 无线: Intel wifi ac3165
- 电源: 内置电源

### BIOS设置

```
System Configuration
  |-- SATA Operaition: AHCI

Video
  |-- Primary Display: Intel HD Graphics

Security
  |-- PTT Security/PTT On: Disabled

Secure Boot
  |-- Secure Boot Enable: Disabled
  |-- Secure Boot Mode: Audit Mode


Intel Software Guard Extensions
  |-- Intel SGX Enable: Disabled

PowerManagement
  |-- Deep Sleep Control: Disabled
  |-- USB Wake Support:   Disabled
  |-- Wake on LAN/WLAN:   Lan only
  |-- Block Sleep:        YES
  
Virtualization Support
  |-- Intel VT for Directed I/O: Disabled
  
POST Behavior
  |-- Fastboot: Minimal

```

### 注意

- 使用 [OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/) 替换三码

