# UNPv2 4.8 单服务器，多客户端
---

客户端把（自身PID，文件路径）写给服务端知名FIFO中，然后服务端解析，然后读文件，写回到客户端对应的FIFO中。

![](fifocliserv.png)


