# OpenCore-EFI-For-MSI-MPG-X570-Gaming-Plus-and-Ryzen-3700X
-------
## 说明

**这是一个黑苹果引导，基于OpenCore制作qwq**

**目前OpenCore版本为0.9.3 支持macOS 14.0 Beta**

**macOS Catalina Bigsur Monterey Ventura之前测试过均可引导，其余系统自测**

----

## 总览
![overview](https://github.com/NikoRurQwQRuaa/OpenCore-EFI-For-MSI-MPG-X570-Gaming-Plus-and-Ryzen-3700X/blob/main/Photos.png)

---

**我的电脑配置：**

**CPU:AMD Ryzen 3700X**

**内存:32GB DDR4 3200Mhz**

**显卡:AMD Radeon RX 570 8GB**

**主板:MSI MPG X570 GAMING PLUS**

----
## 驱动支持方面
---
部件|型号|是否支持
:-|:-|:-|
CPU|AMD Ryzen 7 3700X|支持
独立显卡|MSI AMD Radeon RX570 8GB|支持
网卡|RealtekRTL8111|支持
硬盘|闪迪SATA 128G SSD|支持，三星m.2 PM981a不支持
HDMI输出||支持
音频/3.5耳机接口|Realtek ALCS1220A|支持
内存|金士顿/海盗船DDR4 3200MHz|支持
USB|支持大部分USB3.0 20接口|背板部分2.0无法使用
PS/2接口|自行加驱动VoodooPS2测试|未知
麦克风|ALCS1220A|不支持 使用USB外接解决

## Tips：
**USB驱动是在MacPro7,1的机型下定制的 如需使用请设置三码为MacPro7,1**

**此理论X570机型通用 不保证一定可用，请自行测试**

**初次安装建议在boot-args加入-v跑代码模式 方便排查错误**

**RX5000 6000系列显卡请在boot-args加入agdpmod=pikera**

**机型三码已经删除 请自行使用工具加入**

--
## 致谢

**Acidanthera的OpenCore**

**Apple的macOS**

**AMD Vanilla开发的AMD Ryzen CPU Patch**
