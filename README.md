# Easy OS

## Chinese

Easy OS是一个轻量级的嵌入式操作系统，2~3K的内存即可跑起来，适用于资源有限的各种单片机。
之所以命名为Easy OS是希望以简单的方式，少量代码实现这个OS。

特点：
* 原创任务调度算法，避免使用链表管理任务，任务通过位图，哈希表实现高效查找。
* 高效的内存管理算法，尽可能避免内存碎片。
* 更少的内存开销，2~3K的RAM即可运行，使用于资源有限的单片机。
* 内核层驱动层使用信号槽进行通讯。
* 系统实现方式简单易懂。

## English

Easy OS is a light weight Embedded System, aim at those microcontrollers which have not
to much RAM. 2~3K RAM is enough for Easy OS to run.

Features:
* I utilized a whole new schedule algorithm for Easy OS. I didn't use chain to link the
  tasks, thus, there is no ready task chain and no need to traverse chain to find task.
  In Easy OS, bitmap and hash table is utilized to manager task.
* Efficient memory manage algorithms are provided.
* Low memory useage, 2~3K RAM is enough for Easy OS.
* Signal & Slot are utilized for communication between two different layers.
* I try to keep the OS implementation as simple as I can.


To be continue

Easy OS will be ported to more platforms.
......