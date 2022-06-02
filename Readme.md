# HP_Z840_Hachintosh_OC
## 配置
    惠普Z840工作站
    E5-2643v3 * 2 
    64GB 2133 DDR4 ECC RAM  
    NVIDIA Quadro K6000
    NVIDIA GeForce GTX 560 已拆除
    海康威视 C2000PRO 1TB 
    LSI RAID 卡工作正常
    MacOS 12.4 (21F79)
    BIOS 最新版本  02.50 Rev.A
    OC v0.8.1

## 目前工作正常
   <!-- WIN10 全部正常
    MACOS 10.15.5 工作正常
    MACOS 10.13.6 安装NV WEB DRIVER 工作正常
    MACOS 11.0.1 -->
    MACOS 12.4
## 已知问题
    CFG-LOCK 未解锁 
    CPU 可以变频
    显卡无法硬解码 H264 
    PM981 会引起各种个样莫名其妙的问题 已经拆下来了
    禁用了一个网口 否则会导致死机
    K6000 显卡在12.4中已经不受支持 可以通过这个补丁来使用之前的驱动 
    Geforce Kepler patcher (https://github.com/chris1111/Geforce-Kepler-patcher)