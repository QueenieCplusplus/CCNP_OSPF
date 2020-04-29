# CCNP OSPF

https://github.com/QueenieCplusplus/Static_and_Dynamic (see dynamic routing for private IP)

因於本來的 RIP、IGP 無法處理大型網路，所以才有 OSPF、IGRP、EIGRP 的出現。在處理大型的互聯網路中，OSPF 整體表現比 RIP 好很多。

OSPF 與 IGRP 不同之處在於，前者支援 VLSM (Variable Length Subnet Mask)。

# OSPF, 開啟最短路徑為第一


- [x] Speed of Convergence Optimization using Parallel Computing. 使用平行運算方式處理路徑問題。


- [x] Support VLSM, 支援可變動長度子網路遮罩。


- [x] Network Reachability, 網路觸及範圍：
   
     * RIP: max: 15 hops
     
     * OSPF: without limitation
     

- [x] Method for Path Selection, 路徑選擇方式：

     * RIP: hop count
     
     * OSPF: cost == connection speed
     
  
- [x] Usage of Band Width, 佔用頻寬

     * RIP: Broadcast / 30 sec
     
     * OSPF: Broadcast while changed occurs
     
https://github.com/QueenieCplusplus/OSPF (LSA, Link-State Advertisement, 鏈結層通告)
