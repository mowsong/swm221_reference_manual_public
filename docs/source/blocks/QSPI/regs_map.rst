.. ----------------------------------------------------------------------------------------------------

.. flat-table::
   :header-rows: 1
   :class: tight-table-reg-map

   * - 名称

     - 偏移

     - 类型

     - 复位值

     - 描述

   * - :cspan:`4` QSPI				BASE： 0x40001800

   * - CR

     - 0x00

     - R/W

     - 0x00000000

     - QSPI控制寄存器

   * - DCR

     - 0x04

     - R/W

     - 0x00000000

     - QSPI设备配置寄存器

   * - SR

     - 0x08

     - RO

     - 0x00000000

     - QSPI状态寄存器

   * - FCR

     - 0x0C

     - R/W

     - 0x00000000

     - QSPI标志清零寄存器

   * - DLR

     - 0x10

     - R/W

     - 0x00000000

     - QSPI 数据长度寄存器

   * - CCR

     - 0x14

     - R/W

     - 0x00000000

     - QSPI传输配置寄存器

   * - AR

     - 0x18

     - R/W

     - 0x00000000

     - QSPI地址寄存器

   * - ABR

     - 0x1C

     - R/W

     - 0x00000000

     - QSPI交替字节寄存器

   * - DATA

     - 0x20

     - R/W

     - 0x00000000

     - QSPI数据寄存器

   * - PSMSK

     - 0x24

     - R/W

     - 0x00000000

     - QSPI轮询状态掩码寄存器

   * - PSMAT

     - 0x28

     - R/W

     - 0x00000000

     - QSPI轮询状态匹配寄存器

   * - PSITV

     - 0x2C

     - R/W

     - 0x00000000

     - QSPI轮询间隔寄存器

   * - SSHIFT

     - 0x40

     - R/W

     - 0x00000000

     - QSPI延迟采样寄存器



