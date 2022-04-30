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

![Image text](https://raw.githubusercontent.com/lee-namc/Lenovo-V310-15IKB-Hackintosh/master/Screenshots/OVERVIEW.png)

## 不工作

SD读卡器

4k@60hz输出（dvmt改到64m也无法识别出4k分辨率）



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

基本正常，hevc加速不可用



## Intel无线

·Intel Dual Band Wireless-AC 3165

![Image text](https://raw.githubusercontent.com/lee-namc/Lenovo-V310-15IKB-Hackintosh/master/Screenshots/WIFI.png)

![Image text](https://raw.githubusercontent.com/lee-namc/Lenovo-V310-15IKB-Hackintosh/master/Screenshots/ITLWM.png)

定位

相关链接

https://github.com/OpenIntelWireless/itlwm

https://github.com/OpenIntelWireless/IntelBluetoothFirmware

注释：

· 驱动不再依赖"Heliport"应用程序，请删除"Heliport"。

· 使用此EFI后需重新登录Apple ID以启用以下功能

  接力：在Monterey中不能工作，推测是驱动问题

· 随航(Sidecar)在Wi-Fi下不可用，USB连接正常

  隔空投送可以显示出设备名称但不可用。

![Image text](https://raw.githubusercontent.com/lee-namc/Lenovo-V310-15IKB-Hackintosh/master/Screenshots/Wi-Fi系统信息.png)

![Image text](https://raw.githubusercontent.com/lee-namc/Lenovo-V310-15IKB-Hackintosh/master/Screenshots/随航（Wi-Fi下不可用）.png)

![Image text](https://raw.githubusercontent.com/lee-namc/Lenovo-V310-15IKB-Hackintosh/master/Screenshots/隔空投送（不可用）.png)

## USB

若有问题，用Hackintool重新定制USBPorts.kext即可

![Image text](https://raw.githubusercontent.com/lee-namc/Lenovo-V310-15IKB-Hackintosh/master/Screenshots/USB.png)

## 触摸板

手势尚未修改（平日用鼠标），大多数可以使用



## HiDPI（可选）

![Image text](https://raw.githubusercontent.com/lee-namc/Lenovo-V310-15IKB-Hackintosh/master/Screenshots/HIDPI.png)

https://github.com/xzhih/one-key-hidpi



### 此EFI文件经测试可用

#### Apr 30,2022
