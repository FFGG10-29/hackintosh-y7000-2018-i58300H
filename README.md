# hackintosh-y7000-2018-i58300H  
opencore 引导，big sur11.2.1，y7000 2018款 CPU i5-8300H   

基于当前最新的 open core 0.6.5 版本  

###  硬件需求
其实硬件只有以下限制，网卡我由于太穷。直接30块顺丰的 Intel，不完美但能用，换白苹果卡的话，可以完美（价格太贵）。
```
处理器              英特尔 Core i5-8300H  
硬盘                非三星pm981即可y
网卡                英特尔 Wireless-AC 9560
```

### EFI 描述  
``` 
FN 功能键正常使用，能够正常调整亮度/音量等。  
小键盘正常（开机不会自动开启小键盘锁定，需要手动按一下 Num Lock）  
休眠正常，但不建议休眠，建议使用 Caffeinated 应用禁用睡眠    
Intel 9560AC  蓝牙/ Wi-Fi 正常驱动，如果是换了白果卡，请替换Wi-Fi与蓝牙的kext文件  
电源管理正常  
核显正常，并调整显存为 2048  
USB 正常  
触控板多点触控正常，手势正常。实体键无法使用（即那两个左右按键）
触控与小键盘的驱动是定制的，请不要升级。  其他驱动可随对应的开源项目版本升级     

三码是随机生成的，如果App Store等无法正常使用，请自行修改，这个具体网上一堆的教程。  
```

### 已知问题  
``` 
独显无法正常，HDMI、DP、Type-C 都是连接的独显，所以HDMI与DP都无法用， 这个全网无解， macOS 已抛弃 N 卡。 期待后续有大佬能够填坑，不过，成功的几率微乎其微。   

插耳机的话需要在偏好设置中将声道调至最左或最右  
```

### 补充说明  
- 强烈推荐开启 HIDPI，https://github.com/xzhih/one-key-hidpi  选择分辨率步骤选手动输入，输入 1920x1080，之后使用 RDM 选择 1080 开启，达到最优体验。  

### 感谢    
感谢 “我心飞扬” 大佬的帮助 以及 其他各个使用到的开源项目（太多就不一一列举） 

### Alliot's blog  
[Alliot's blog](https://www.iots.vip)  
