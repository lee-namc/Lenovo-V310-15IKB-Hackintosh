# Lenovo V310-15IKB Hackintosh

| 规格     | 详细信息                     |
| -------- | ---------------------------- |
| CPU      | i5-7200U                     |
| GPU      | HD 620                       |
| Memory   | 12 GB                        |
| Storage  | 1TB WD 5400RPM HDD           |
| Wireless | INTEL AC3165                 |
| 操作系统 | Big Sur 11.0.1-Clover-5126  |

更换序列号以登录Apple ID

天翼云盘：网址稍后添加

## 不工作

SD读卡器

## 未测试

VGA

## 可能不适用于

配备双电池的设备



## Bios 设置

BOIS Version : 2WCN46WW

Configuration > Graphic Devices > UMA only

Security > Secure Boot>关闭

Boot > ATA HDD调至第一顺序



## 显卡
笔记本内建显示器色彩有断层，注入EDID/使用0x1916均无法解决




## Intel无线

·Intel Dual Band Wireless-AC 3165

https://github.com/OpenIntelWireless/itlwm

https://github.com/OpenIntelWireless/IntelBluetoothFirmware

## 驱动由itlwm换为AirportItlwm集成在EFI中，不再需要Heliport。使用此EFI需重新登录Apple ID，这样才能启用AppleWatch的解锁功能（不稳定且未测试）。随航、接力在本人设备上均无效果，隔空投送仅能显示出设备，但无实际作用





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
