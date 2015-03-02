Network Programming
===

Every network application is based on **client-server**
model. The atomic operation is **transaction**.

##网络

对于主机而言，网络只是又一种IO设备。

物理上而言，网络是一个按照地理远近组成的层次系统。最低层次是**LAN**，Local
Area Network。

互联网络只管重要的特性是：它能由采用完全不同和不兼容技术的各种局域网和广域网
组成。没太主机和其他主机都是物理相连的。

达成这个目的的方法是运行在每台主机上和路由器上的协议软件，它消除了不同网络之间
的差异。这种协议提供两种基本能力：

+ 命名机制。
+ 传送机制。在电缆上编码位和将这些封装成帧方面，不同的联网技术有不同的和不兼容
的方式。互联网协议通过定义一种把数据位捆扎成不连续的片（包）的统一方式，从
而消除这些差异。
