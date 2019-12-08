# OMNeT++仿真平台 #

## OMNeT++简介 ##

<<<<<<< HEAD
**OMNeT++**，一个基于<b>Eclipse</b>开发套件的开源网络仿真工具，目前主要在高校实验室进行一些网络仿真测试，对一些算法进行对比，它可以供使用者进行完成以下开发：
=======
<b>OMNeT++</b>，一个基于<b>Eclipse</b>开发套件的开源网络仿真工具，目前主要在高校实验室进行一些网络仿真测试，对一些算法进行对比，它可以供使用者进行完成以下开发：
>>>>>>> upstream/master

- **C/C++开发**
- **网络仿真程序设计**

毫无疑问，基于<b>Eclipse</b>的开发工具肯定能支持普通的<b>C/C++</b>工程。
另外，在<b>OMNeT++</b>上网络仿真设计领域的优势在于，它是一个开源的项目，对大量的网络模型都提供代码支持。但是问题在于国内的确没有什么社区支持，出现问题只能自己解决，其实对于开源的项目大多存在这种问题，往往开源的项目，使用起来难度较大，开源项目往往比那些商业的软件开发难度较大，支持也较少，开源可不代表简单。

<b>OMNeT++</b>对初学者能力要求高，它假定使用者对编程有一定了解的，对eclipse开发环境也是特别熟悉的，另外这是一个网络仿真的软件，需要你对计算机网络有足够的认识，它提供了大量现有各种网络的仿真例子，如果你对网络认识足够强，那么这个软件你用起来会感到特别顺手。</br>
目前有大量的开源仿真库用于OMNeT++环境，拥有丰富的外文资料，官方将其分为两类，包括Supported Models和Contributed Models：</br>

- Supported Models

模型库的开发处于激活状态，有开发者在维护，定期会推出新的版本。

- Contributed Models

完成后只推出过一次或几次版本，目前没有人在维护。</br>

## OMNeT++开源库 ##

下面简单介绍一下几种常见的开源库。

### INET ###

由Simucraft公司主持开发，用于仿真有线及无线网络。

- 应用层协议：HTTP、FTP、Telnet、不同优先级的 Video、Ping；

- 传输层协议：TCP、UDP、RTP ( RealtimeTransport Protocol )；

- 网络层协议：IPv4、IPv6、OSPF、AODV、DSDV、DSR等；

- 数据链路层协议：Ethernet、PPP、IEEE 802.11、FDDI、Token Ring；

- 官网：<http://inet.omnetpp.org>

### INETMANET ###

由 Simucraft 公司主持开发，用于仿真无线、有线网络，在INET的基础上增加了大量的MANET协议，INETMANET=INET+MANET，在INET的基础上增加：

- 802.11a

- Ieee80211Mesh,Ieee80211MeshMgmt

- radiomodels: TwoRayModel, ShadowingModel, qamMode

- Ns2MotionMobility

- ARP:global ARP cache

- AODV,DSDV, DSR, DYMO, OLSR

- 官网：<http://inet.omnetpp.org>

### Mobility Framework ###

由 Simucraft 公司主持开发,是一个无线传感器仿真模型库.绝大多数协议已经被 INET 吸收

- 官网：<http://mobility-fw.sourceforge.net/hp/index.html>

### SensorSimulator ###

美国路易斯安娜州立大学开发,用于仿真无线传感器网络

- 官网：<http://csc.lsu.edu/sensor_web/>

### Castalia ###

澳大利亚国家信息技术中心（NICTA）开发,是一个基于 OMNeT++ 的侧重于无线网络的仿真器。基于实测数据的高级 channel/radio 模型，Radio 详细的状态转移，允许多传输功率电平。

- 高度灵活的 physical process model

- 感应设备的噪声、偏差（bias）和功耗

- 节点时钟漂移，CPU 功耗

- 资源监控，如超出功率限制（如 CPU 或内存）

- 拥有大量可调参数的mac协议

- 用于设计优化和扩展

- 官网：<https://github.com/boulis/Castalia>

### OverSim ###

德国卡尔斯鲁厄大学开发

- 用于仿真点对点（p-to-p）协议，如chard，GIA等

- 官网：<http://www.oversim.org>

### TTE4INET ###

由Communication over Real-Time Ethernet Group开发的时间触发以太网仿真模型，包括对AS6802的仿真实现。现仿真模型已改名为CoRE4INET。

- 开发组主页：<https://core.informatik.haw-hamburg.de/>

其他更多的OMNeT++开源仿真模型可浏览以下网站：

<https://omnetpp.org/download/models-and-tools>
<<<<<<< HEAD
=======

>>>>>>> upstream/master
