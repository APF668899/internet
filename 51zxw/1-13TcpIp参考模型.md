# TCP IP参考模型
## TCP/IP模型一共四个层
1. 应用层
   * 应用层(Application)
   * 表示层(Presentation)
   * 会话层(Session)
2. 传输层
   * 传输层(Transport)
3. 网际层(Internat)
   * 网络层(Network)
4. 网络访问层(Network Access)
   * 数据链路层(Data Link)
   * 物理层(Physical)

## 网络访问层
1. 网络访问层的功能包括IP地址与物理硬件地址的映射,以及将IP地址封装成帧。
2. 基于不同类型的网络接口，网络访问层定义了和物理介质的连接
3. 网络访问层包含了数据链路层的地址，因为可以看到源MAC和目标MAC
4. 它是TCP/IP协议的最底层，负责接收从网际层传来的IP数据报，并且将IP数据报通过底层物理网络发出去。或者从底层的物理网络上接收物理帧，解封装出IP数据报，交给网际处理
