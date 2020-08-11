# Lenovo V310-15IKB Hackintosh

| 规格     | 详细信息                     |
| -------- | ---------------------------- |
| CPU      | i5-7200U                     |
| GPU      | HD620                        |
| Memory   | 12 GB                        |
| Storage  | 1TB WD 5400RMP HDD           |
| Wireless | INTEL AC3165                 |
| 操作系统 | Catalina 10.15.6-Clover-5119 |

## 已知问题



## Bios 设置

Security >Secure Boot>关闭

Boot >ATA HDD调至第一顺序

## 显卡

仿冒0x19160000

## Intel无线

·Intel蓝牙

https://github.com/OpenIntelWireless/itlwm

·Intel无线网卡

https://github.com/OpenIntelWireless/IntelBluetoothFirmware

## 安装三个无线驱动和heliport客户端即可，附件中“itlwm.kext”为8月2日版本

## USB

若有问题，可重新定制USBPorts.kext

## 触摸板

手势尚未修改

## HiDPI

https://github.com/xzhih/one-key-hidpi

## HWP

终端输入

cd /tmp && curl -s https://raw.githubusercontent.com/Piker-Alpha/freqVectorsEdit.sh/master/freqVectorsEdit.sh > /tmp/freqVectorsEdit.sh && chmod +x freqVectorsEdit.sh && /tmp/freqVectorsEdit.sh && sudo rm -rf /tmp/freqVectorsEdit.sh && sudo rm -rf /tmp/Mac-*.bin



此EFI文件经测试可用