# CPU
CPU用于数据的运算

组成：
* 算术逻辑单元(ALU)
* 控制单元
* 寄存器组
* 快速存储定位 


## 算术逻辑单元
1. 逻辑运算

第四章中讨论了几种逻辑运算，如与或非和异或  
这些运算把输入数据作为二进制位模式，结果也是二进制位模式

2. 移位运算

第四章讨论了数据的两种移位运算：
* 逻辑移位运算

用来对二进制位模式进行向左或向右的移位

* 算术移位运算

运用于整数，用途是乘以2或除以2


3. 算术运算
第四章我们讨论了整数和实数的一些算术运算

## 寄存器
> 用来存放临时数据的高速独立的存储单元  
> cpu运算离不开大量寄存器的使用


1. 数据寄存器

> 计算机只有几个数据寄存器用来存储输入数据和运算结果  
> 现在许多复杂运算改由硬件设备实现而不是使用软件  
> 所有计算机在CPU中使用几十个寄存器来提高运算速度，并且需要一些寄存器来保存这些运算的中间结果  
> 数据寄存器被命名为R1 到 Rn

2. 指令寄存器

> 计算机存储的不仅是数据，还有存储在内存中相应的程序  
> CPU的主要职责是从内存中逐条地取出指令，并将取出的指令存储在指令寄存器中，解释并执行指令


3. 程序计数器

> 程序计数器中保存着当前正在执行的指令  
> 当前指令执行完后，计数器自动+1，指向下一条指令的内存地址

## 控制单元
> 控制各个子系统的操作  
> 控制是通过从控制单元到其他子系统的信号来进行






