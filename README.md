# Ubuntu_issues

## 电脑相关的
G7 7590-2765

处理器：
    i7-9750H
        4.5GHz  6核心  12线程
内存：
    16GB
注意：没有机械硬盘
固态硬盘：
    512GB PCIe SSD
15.6英寸显示屏
    1920 × 1080 IPS 72%色域 144Hz 全高清 防眩光
显卡：
    GTX 1660Ti 6GB

2019.07.29
    淘宝 - 戴尔官方旗舰店: 10998.90元
    京东 - 戴尔官方旗舰店: 10999元


## sudo apt-get related issues
a.
问题描述：
    The following signatures couldn't be verified because the public key is not available: NO_PUBKEY F42ED6FBAB17C654
解决办法：
    sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys F42ED6FBAB17C654
