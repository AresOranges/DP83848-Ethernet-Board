# DP83848-Ethernet-Board    
记录移植DP83848从client客户端到server服务端的过程    

为什么要移植？   
因为如果单片机是client客户端的话，你可以把它理解为是客人，需要向电脑发出请求，电脑同意了之后才能建立连接。  
而server相当于是主人，在电脑端向它发送请求，它接收到了之后就可以建立连接，互相发送数据了。  

LWIP有3种编程接口，分别为：RAW，NETCONN和SOCKET。 

MAC,PHY芯片有什么区别？  
一块以太网网卡包括OSI模型中的两个层：物理层和数据链路层。  
物理层的芯片简称PHY 
数据链路层的芯片简称MAC 
有些网卡的芯片把MAC和PHY的功能做到了一颗芯片中，但是MAC和PHY的机制还是单独存在的，只是外观的表现形式是一颗单芯片。 












