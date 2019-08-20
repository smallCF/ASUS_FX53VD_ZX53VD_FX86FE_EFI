### `支持安装的设备: FX53VD/ZX53VD(i5-7300HQ/I7-7700HQ)`
- (远景论坛流通的GL553VD笔记本电脑EFI均由本人早期EFI派生而来,第一作者：QiuChenly(秋城落叶))
- (所有开源驱动非本人制作，我只是将这些驱动结合在一起打造一台基本完美的黑苹果工作站。感谢国外各个开源项目。)
##  Author:QiuChenly
>  **如果发现部分硬件本应该工作却没有工作,请至华硕官网下载307版本BIOS固件进行BIOS更新.** 
>> **华硕FX53VD 飞行堡垒个人交流群（QQ群文件同步更新EFI）:** 
>>> ![alt tag](https://raw.github.com/QiuChenly/ASUS_FX53VD_10.13.1EFI/master/macOS10.12_98%25%E5%AE%8C%E7%BE%8Eefi/QQ.jpg)
# 最新 EFI V9.3
# 最新 测试版EFI : Catalina DP5
# [Download](EFI - 9.3.zip)
# [Download DP5](EFI - Catalina DP5.zip)
(最新 - 2019.8.20日更新，更新已转移到中国科技大学校内公共托管服务器.)

## 简单问答,完整版看最后.

## 问答区:
## 我想安装macOS Catalina DP6,该怎么操作?
### 请先使用DP5这个EFI安装完DP6,随后使用EFI - 9.3.zip替换你的引导即可正常使用.
####  注意:macOS 10.15无法使用Fn键调节键盘背光.

## 安装过程中卡死在进度条,使用了你的EFI - 9.X版本,怎么办?
### 请使用DP5这个EFI来完成安装,随后使用EFI - 9.3.zip替换为你的引导即可.
#### 注意:fn键快捷键仅在macOS 10.14(-)系统上可用.

## 1.这个EFI哪些机器可以用?
### FX53VD,ZX53VD,以及其他基于GL553这个主板的笔记本电脑.
## 2.EFI我该下载哪一个?
### [EFI - 9.3.zip](EFI - 9.3.zip)
## 3.这个EFI还存在什么问题吗?
### 没有了-除了无法驱动独立显卡.这台电脑的独立显卡没有办法可以驱动---嘘,别问为什么,问就请闭嘴.
## 4.请问触控板/声卡/网卡/无线网卡和蓝牙/....可以驱动吗?
### 请你看一下第三条.如果不懂,那就记得四个大字:全都驱动了.
## 5.我的原装Intel无线网卡无法驱动是怎么回事?
### 无法驱动就无法驱动.换个能驱动的网卡会吗?你妈的,这种问烂了的问题你自己不会百度搜?每天问这种弱智问题,我很不高兴.
## 6.用这个EFI有什么注意事项吗?
### 你如果不懂EFI怎么修改,那就不要动这个EFI内的任!何!文!件!如果你自认为很懂,那请你滚去自己弄,出问题不要问,我没兴趣帮你解答.
## 7.声卡没加载是怎么回事?
### 重建驱动缓存.
## 8.原装的Intel无线网卡无法驱动怎么办?蓝牙好像驱动了.
### 去淘宝买943602CS+转接板装到笔记本里.
## 9.买回来不会装怎么办QAQ
### 怎么着,我还帮你装好了给你?不会动手只会等别人弄好了给你的废物就不要玩黑苹果.
## 10.触控板没法用啊!
### 重建驱动缓存.
## 11.装完之后出现了xx问题怎么办?
### 先去重建一遍驱动缓存再来问我.
## 12.键盘Fn键可以用吗?
### 请参考第四条的答案.看不懂中文?没关系:no,all devices is done,works very nice.
## 13.从Windows下重启到了macOS,发现笔记本外放无声,怎么办?
### 关机,再开机直接进macOS.我没兴趣跟你讲原理,反正不是我的问题.
## 14.完整版的问答在这里:[README_FULL.md](README_FULL.md)
