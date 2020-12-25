# proj25-rt-device-tree
### 项目描述

本项目在RT-Thread/RT-Thread Smart操作系统上增加设备树的功能。设备树是一种**通行的**描述硬件资源的数据结构。它通过bootloader将硬件资源传给内核，使得内核和硬件资源描述相对独立。

### 所属赛道

2021全国大学生操作系统比赛的“OS功能设计”赛道



### 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生（2021年春季学期或之后本科毕业的大一~大四的学生）
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2021全国大学生操作系统比赛”的章程和技术方案要求



### 项目导师

**Bigmagic**

* github [bigmagic](https://github.com/bigmagic)

* email haofujin@rt-thread.com



### 难度

简单



### 特征

在RT-Thread上实现设备树功能，包括对DTC（device tree compiler），DTS（device tree source和DTB（device tree blob）支持。同时在K210上可以使用设备树来描述周边外设。



### 参考实现

https://github.com/RT-Thread/rt-thread

https://github.com/dgibson/dtc

### License

* [Apache-2.0](https://opensource.org/licenses/Apache-2.0)



## 预期目标

### 注意：下面的内容是建议内容，不要求必须全部完成。选择本项目的同学也可与导师联系，提出自己的新想法，如导师认可，可加入预期目标

### 第一题：在RT-Thread上支持设备树基本功能

在RT-Thread上加入设备树的功能，能够在Host PC上对设备树进行编译，同时在RT-Thread上能够对设备树二进制数据进行解析。最终把设备树相关的功能制作成RT-Thread上的一个软件包；

### 第二题：在设备树中加入更多的K210外设

在K210的RT-Thread版本中加入基本外设描述，例如GPIO，UART，SPI，IIC等。同时在RT-Thread设备驱动框架中对接设备树种类的支持；