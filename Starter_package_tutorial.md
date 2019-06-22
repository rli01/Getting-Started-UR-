# 如何使用URCaps Starter Package

UR Starter Package 是优傲官方提供的给UR+开发者的一个集成开发环境。 因为UR的开发环境是在linux下， 它的目的是给一些不熟悉linux或者不常使用linux的开发者搭建一个现成的开发环境。使开发者更专注与开发本身，而非浪费时间和精力在linux开发环境的搭建上。

>>>对于一些常年在Linux下开发的开发者， UR官方也提供了URCap开发的SDK。

## Starter Package 的内容

开发包是一个虚拟机的镜像文件， 他里面的内容主要有以下的四个部分。
![开发包内容](urStartPackage.png "开发包")

### 下载链接

StarterPackage 可以官网下载，如果你有比较快的vpn的话, 也可以通过百度云盘
[StarterPackage universal-robots 官网](https://plus.universal-robots.com/download-center/urcaps-starter-package/ '官网')

[StarterPackage 百度云盘](https://pan.baidu.com/s/1cTHYoIV2Jb7A7TZvWbyu9Q '百度云盘')
>提取码： o3sz （因百度网盘单个文件限制， 通过百度网盘下载的一共有7个分开的解压包，务必保证解压包的完整）

### ubuntu64位的系统

开发包解压之后是一个虚拟机的ubuntu 64 位的系统镜像， 也就是说你需要通过虚拟机软件来运行，主流的虚拟机软件有VMware 和 VirtualBox。
[VirturalBox](https://www.virtualbox.org/)

[VMware](https://www.vmware.com/) 推荐
>请自行百度， 根据自己的喜好下载。

安装好虚拟机软件后，你就可以打开我们这个StarterPackage这个系统, 界面如下：

![系统界面](ubuntu.png)
在界面中，你可以看到6个UR的蓝色图标， 这是我们机器人的模拟器，3代表cb3系列，3.8对应的软件版本， 5代表Eserie系列的5.2软件版本 。 最后的UR3，UR5，UR10分别对用我们机器人3,5,10型号。

### Eclipse IDE

Eclipse IDE 是主流的 Java开发的一个开源的IDE， UR官方已经为开发者们配置好了Maven 等一些开发必须的工具。

![Eclipse IDE](eclipse.png)

### URSim

前面已经说过了URSim是一个UR机器人的模拟器， 他可以真实的模拟出和我们在示教器上一样的软件环境。对于UR+的开发者来说，开发的URCap插件也可以在URSim上仿真模拟。

### URSDK

UR 官方提供的一个软件开发包，用来URCap的开发，包括了基于Java的API、教程和示例程序