# linux路由，网关，子网掩码

## linux路由

执行命令/sbin/route查看路由表

```
Kernel IP routing table
Destination     Gateway         Genmask         Flags Metric Ref    Use Iface
30.0.0.0        xxx.xxx.xxx.xxx  255.0.0.0       UG    0      0        0 eth0
default         xxx.xxx.xxx.xxx  0.0.0.0         UG    0      0        0 eth1
```

```
1. Gateway表示网关，Genmask表示子网掩码
2. default一行表示公网路由(子网掩码0.0.0.0代表公网)
```

## 网关
- 是一个网络通向其他网络的一个ip地址。
- 不同网络中的主机通讯需要经过网关

## 子网掩码
- 和ip地址一起，用来将IP地址划分成网络地址和主机地址两部分



