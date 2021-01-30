# Lenovo V310-15IKB Hackintosh

| 规格     | 详细信息                     |
| -------- | ---------------------------- |
| CPU      | i5-7200U                     |
| GPU      | HD620                        |
| Memory   | 12 GB                        |
| Storage  | 1TB WD 5400RPM HDD           |
| Wireless | INTEL AC3165                 |
| 操作系统 | Catalina 11.1-Clover-5126    |

更换序列号以登录Apple ID

天翼云盘：网址稍后添加

## 已知不工作

SD读卡器

## 未测试

VGA

## 可能不适用于

安装了双电池的设备



## Bios 设置

BOIS Version : 2WCN46WW

Configuration > Graphic Devices > UMA only

Security > Secure Boot>关闭

Boot > ATA HDD调至第一顺序



## 显卡





## Intel无线

·Intel蓝牙&无线网卡

https://github.com/OpenIntelWireless/itlwm

https://github.com/OpenIntelWireless/IntelBluetoothFirmware

## 驱动由itlwm换为AirportItlwm，不再需要Heliport，但不支持接力和隔空投送



## USB

若有问题，可重新定制USBPorts.kext



## 触摸板

手势尚未修改（平日用鼠标）



## HiDPI

https://github.com/xzhih/one-key-hidpi



## HWP（可选）

终端输入

cd /tmp && curl -s https://raw.githubusercontent.com/Piker-Alpha/freqVectorsEdit.sh/master/freqVectorsEdit.sh > /tmp/freqVectorsEdit.sh && chmod +x freqVectorsEdit.sh && /tmp/freqVectorsEdit.sh && sudo rm -rf /tmp/freqVectorsEdit.sh && sudo rm -rf /tmp/Mac-*.bin

## 此EFI文件经测试可用
Jan 30,2021
