
.. toctree::
  :maxdepth: 2
  
    
系统管理 (SYSCON)
=========================

概述
----
系统管理为整个芯片提供时钟源，包括系统时钟切换、外设时钟门控、工作模式选择以及版本控制等功能。还可通过单独时钟的开或关，时钟源选择来进行功耗控制。


特性
----
-  时钟控制

-  浅睡眠模式

-  端口唤醒设置

-  低电压复位LVR

-  可编程电压检测PVD

-  UID

-  复位控制及状态

..

   支持上电/断电（POR/ PDR）、LVR 复位

特殊用途IO的复位状态：PB15、 PB2 Pull-up， PB11 、PB10Pull-down


   
功能描述
--------
.. include:: functions.rst


寄存器映射
----------
.. include:: regs_map.rst


寄存器描述
----------
.. include:: regs_tables.rst

