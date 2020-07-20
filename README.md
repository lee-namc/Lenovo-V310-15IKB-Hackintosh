# Lenovo V310-15IKB Hackintosh

CPU	i5-7200U

GPU	HD620 2048 MB

Memory	12 GB 2133 MHz DDR4

Storage	1TB WD 5400RMP HDD

Wireless	INTEL AC3165 Wifi&Bluetooth

备注	单电池，屏蔽独立显卡

支持系统	Catalina 10.15.6-Clover-5119

*此EFI可能与部分E42-80和Ideapad 310机型有相似之处，可能兼容

*HDMI&VGA未测试

*可以直接使用此EFI引导安装程序

*自行定制USBPorts，默认加入

*自行注入三码以登录Apple ID

Intel无线

·Intel蓝牙

https://github.com/OpenIntelWireless/itlwm

·Intel无线网卡

https://github.com/OpenIntelWireless/IntelBluetoothFirmware

http://bbs.pcbeta.com/forum.php?mod=viewthread&tid=1848662

*IntelBluetoothFirmware.kext，IntelBluetoothInjector.kext，itlwm.kext三个kexts文件过大，独立打包在IntelWireless.zip中。解压后放入kexts文件夹

*iitlwm.kext配置方法（来自远景论坛）

第一步,找到驱动右键,显示包内容:

第二步,找到info.plist,打开编辑

第三步,用xcode或plisteditor编辑（如itlwm.png所示）将密码跟ssid换成你的Wi-Fi即可

第四步,用命令加载或者丢到clover/oc的kext目录下重启即可自动连接上Wi-Fi.

*如果在使用过程中需要添加Wi-Fi但是又不想重启,可以用以下命令卸载,然后编译好之后再次加载

卸载: 

sudo kextunload -b com.zxystd.itlwm

加载: 

sudo chown -R root:wheel itlwm.kext

sudo kextutil -v 6 itlwm.kext


HiDPI

https://github.com/xzhih/one-key-hidpi

参考
