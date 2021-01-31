# **Lenovo V310-15IKB Hackintosh**

| 规格     | 详细信息                 |
| -------- | ------------------------ |
| CPU      | i5-7200U                 |
| GPU      | HD 620                   |
| Memory   | 12 GB                    |
| Storage  | 1TB WD 5400RPM HDD       |
| Wireless | INTEL AC3165             |
| 操作系统 | Big Sur 11.1-Clover-5126 |

### 注入序列号以登录Apple ID

### 睡眠效果奇怪

### 天翼云盘：

http://dwz.win/KFh

![Image text](https://raw.githubusercontent.com/lee-namc/Lenovo-V310-15IKB-Hackintosh/master/Screenshots/概览.png)

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

可用功能

Wi-Fi 802.11n（速度发挥有限）

定位

相关链接

https://github.com/OpenIntelWireless/itlwm

https://github.com/OpenIntelWireless/IntelBluetoothFirmware

注释：

· 驱动不再依赖"Heliport"应用程序，请删除"Heliport"。

· 使用此EFI后需重新登录Apple ID以启用以下功能

  Apple Watch解锁（不稳定且未测试）

  接力——Handoff

· 随航(Sidecar)在Wi-Fi下不可用，隔空投送可以显示出设备名称但不可用。

![Image text](https://raw.githubusercontent.com/lee-namc/Lenovo-V310-15IKB-Hackintosh/master/Screenshots/Wi-Fi系统信息.png)

![Image text](https://raw.githubusercontent.com/lee-namc/Lenovo-V310-15IKB-Hackintosh/master/Screenshots/随航（Wi-Fi下不可用）.png)

![Image text](https://raw.githubusercontent.com/lee-namc/Lenovo-V310-15IKB-Hackintosh/master/Screenshots/隔空投送（不可用）.png)

## USB

若有问题，用Hackintool重新定制USBPorts.kext即可

![Image text](https://raw.githubusercontent.com/lee-namc/Lenovo-V310-15IKB-Hackintosh/master/Screenshots/USB.png)

## 触摸板

手势尚未修改（平日用鼠标）



## HiDPI（可选）

https://github.com/xzhih/one-key-hidpi

放大有点夸张，建议使用UHD显示器体验原生HiDPI



### 此EFI文件经测试可用

#### Jan 30,2021
