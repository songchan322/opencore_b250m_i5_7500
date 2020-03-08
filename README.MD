# 自用Opencore配置

## 硬件
- cpu： i5-7500
- 主板： 技嘉ga-b250m-ds3h
- 内存： 镁光8g * 2
- 存储： intel 600p 256G
- 显卡： msi rx560 半高
- 声卡： ALC887
- 网卡： RTL8168G/8111G
- 无线网卡：bcm943602cs


## 正常工作的部件
- 正常进系统
- 显卡
- wifi&蓝牙
- airdrop
- airplay（随航不能正常工作）


## 存在的问题
~~ 随机kernal panic，报错 `nvme: "Fatal error occurred. CSTS=0xffffffff US[1]=0x0 US[0]=0xca VID=0x8086 DID=0xf1a5`，暂时没找到解药。~~
2020-02-13 可能是硬件兼容性问题，换了sm963之后，暂时没有出现问题
