# Hackintosh for Asus-H110s1, I3-8100, DW1820A, using Opencore and Support macOS Catalina    

**使用EFI前请务必修改三码(SSN,UUID,ROM)**    
**Please change three system codes (SSN,UUID,ROM) before using this EFI**   

---

2020-04-17 更新：

- Update LiLu to 1.4.3    
- Update Whatevergreen to 1.3.9     
- Update AppleALC to 1.4.8     
- Update CPUFriend to 1.2.0    
- Update NVMeFix to 1.0.2
- Update VirtualSMC to 1.1.2

---

# Hardware/硬件
|  | Specifications / 型号 | Note / 备注 |
|-------------------------|:---------------------------------:|:-------------------------------:|
| Motherboard/主板: | Asus H110s1 | (mini STX) |
| CPU/处理器: | QL2X | (7820HK modify from BGA to LGA) |
| CPU Cooler/散热器: | NOCTUA NH-L9i |  |
| Hard Drive/硬盘: | Hikvision C2000pro 512gb |  |
| RAM/内存: | JUHOR 16G DDR4 2666MHz X2 |  |
| Wireless Card/无线网卡: | BCM94350ZAE | (DW1820A) |
| Tower Case/机箱: | SilverStone VT02 |  |
| Power/电源: | 55/25mm 19v 120w DC power adapter |  |
  
---
# Functions/功能
### Work：
- All HDMI ports (1080p)  
- DP port (1080p)  
- Audio output on HDMI  
- All USB ports  
- Wi-Fi & Bluetooth  
- 3.5mm Audio Output & Mic Input
- Airdrop  
- AirPlay  
- Continuity  

### Not working:
- Sleep  

### Not tested yet:
- 4k display  
  
---

# BIOS setting/BIOS设定：

### Disable：
- Fast Boot  
- CFG Lock   
- VT-d  
- CSM  
- Intel SGX  

### Enable：
- VT-x  
- Above 4G decoding  
- Hyper Threading  

---
# Performance/展示

![image](https://github.com/Road00/Hackintosh_Asus-H110s1_QL2X_DW1820A_OC/blob/master/Figure/8CB768EC-7D4C-49EA-9FDE-12661C0B0B63_1_105_c.jpeg?raw=true)
![image](https://github.com/Road00/Hackintosh_Asus-H110s1_QL2X_DW1820A_OC/blob/master/Figure/%E6%88%AA%E5%B1%8F2020-02-18%E4%B8%8B%E5%8D%886.58.19.png?raw=true)
![image](https://github.com/Road00/Hackintosh_Asus-H110s1_QL2X_DW1820A_OC/blob/master/Figure/截屏2020-01-27下午4.58.51.png?raw=true)
![image](https://github.com/Road00/Hackintosh_Asus-H110s1_QL2X_DW1820A_OC/blob/master/Figure/截屏2020-01-27下午4.54.32.png?raw=true)

---
# Reference/参考

[精解OpenCore](https://blog.daliansky.net/OpenCore-BootLoader.html) - [黑果小兵的部落阁 ](https://blog.daliansky.net/)

[使用OpenCore引导黑苹果](https://blog.xjn819.com/?p=543) - [XJN](https://blog.xjn819.com/) 

[Asrock deskmini 310-com hackintosh 10.14-10.15 EFI](https://blog.xjn819.com/?p=7) - [XJN](https://blog.xjn819.com/)

[分享EFI 华硕H110S1 STX主板 i3-8100 UHD630](http://bbs.pcbeta.com/viewthread-1801615-1-1.html) - [mike20080924](http://i.pcbeta.com/space-uid-3336274.html)

[DW1820A/BCM94350ZAE/BCM94356ZEPA50DX插入的正确姿势](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) - [黑果小兵的部落阁](https://blog.daliansky.net/)
