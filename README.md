<img src="images/mac.png">

# OpenCore EFI

| 版本 | 日期 | 说明 |
| ---- | ---- | ---- |
| 1.0 | 2020.7.23 | 支持 macOS 10.15.7 |

*[下载地址](https://github.com/ZzzM/Hackintosh-MSI-B360M-MORTAR/releases/download/1.0/EFI.zip)*

*[历史记录](https://github.com/ZzzM/Hackintosh-MSI-B360M-MORTAR/releases)*
  
**注意:**
- 三码应重新设置
- 机型应根据配置设置
- BIOS 应根据使用情况设置
  
[*参考地址*](https://github.com/GeQ1an/MSI-B360M-MORTAR-HACKINTOSH-OPENCORE-EFI#%E4%BD%BF%E7%94%A8-efi)

# 功能

- [x] 声卡
- [x] 显卡 / 硬解 4K（HEVC + H.264）
- [x] WiFi & 蓝牙
- [x] 隔空投送 / 接力
- [x] 睡眠 / 键盘、鼠标唤醒
- [x] 原生电源管理

# 配置

| 主要硬件 | 品牌型号 |
| ---- | ---- |
| 主板  | 微星 B360M 迫击炮 |
| CPU  | Intel Core i5-9400F |
| 显卡  | 蓝宝石 RX590（8G D5 超白金 极光特别版） |
| SSD  | 海康威视 C2000 PRO（512G） |
| 内存  | 宇瞻 黑豹系列（8G DDR4 2666）x 2 |
| 电源  | 振华 80PLUS金牌战斗版（550w） |
| WiFi & 蓝牙  | 奋威 BCM94360CD（双频 1750M + 蓝牙 4.0）PCI-E 无线网卡 |

#  性能对比
- 系统：macOS Catalina 10.15.6
- 工具：Geekbench 5.2.0


- 设备：
  - MacBook Pro (Retina, 15-inch, Mid 2015) 
  <img src="images/mac15.PNG">  
  
  - MacBook Pro (16-inch, 2019)  
  <img src="images/mac16.PNG">   

- 结果
  
| 设备 | CPU | 单核 | 多核 |
| ---- | ---- | ---- | ---- |
| 黑苹果 | Intel Core i5-9400F |1025 | 5118 |
| MacBook Pro (Retina, 15-inch, Mid 2015) |Intel Core i7-4770HQ | 821 | 3303 |
| MacBook Pro (16-inch, 2019) | Intel Core i7-9750H | 1073 | 5425 |


| 设备 | 显卡 | OpenCL | Metal |
| ---- | ---- | ---- | ---- |
| 黑苹果 | AMD Radeon RX 590 |38203 | 39163 |
| MacBook Pro (Retina, 15-inch, Mid 2015) | Intel Iris Pro | 5152 | 520 |
| MacBook Pro (16-inch, 2019) | AMD Radeon Pro 5300M </br> Intel UHD Graphocs 630  | 25241 </br> 5186 | 23814 </br> 4718 |


# 参考
- [MSI-B360M-MORTAR-IMACPRO-EFI](https://github.com/andot/MSI-B360M-MORTAR-IMACPRO-EFI)

- [MSI-B360M-MORTAR-HACKINTOSH-OPENCORE-EFI](https://github.com/GeQ1an/MSI-B360M-MORTAR-HACKINTOSH-OPENCORE-EFI)
