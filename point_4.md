# POINT_4         
## 选择题           
1、广义上讲，凡是带有微处理器的专用软硬件系统都可称为嵌入式系统。狭义上讲，嵌入式系统强调那些使用嵌入式微处理器构成的具有自己的操作系统和特定功能、用于特定场合的独立系统。                     
2、根据CPU的字长，微处理器产品有4位、8位、16位、32位和64位之分。                
3、SoC芯片中既包含数字电路，也可以包含模拟电路，甚至还能包含数字/模拟混合电路和射频电路。                    
4、集成电路的工作速度主要取决于组成逻辑门电路的晶体管尺寸。晶体管的尺寸越小，其极限工作频率越高，门电路的开关速度就越快。                    
5、Unicode/UTF-16采用的是双字节可变长编码。ASCII字符、标点符号、希腊字母、阿拉伯文和CJK汉字等均使用双字节编码，其他不常用字符则使用4字节编码。                         
6、一幅图像的数据量可按下面的公式进行计算（以字节为单位）：图像数据量=图像水平分辨率图像垂直分辨率像素深度÷8。                           
7、量化后的样本一般用8位、12位或16位二进制整数表示（称为“量化精度”）。              
8、每个终端设备的IP地址并不是始终固定不变的，而是可以修改的。                   
9、嵌入式处理器的体系结构按指令集可分为两大类：复杂指令集结构（CISC）和精简指令集结构（RISC）。进一步细分，按存储机制分为冯·诺依曼结构及哈佛结构。冯·诺依曼结构中数据和程序统一，使用一条总线；而哈佛结构中使用两条独立的总线，不允许指令和数据并存。指令集和存储机制可以共存。ARM处理器采用RISC结构。                     
10、ARM与Thumb间可以互相切换。如果Thumb状态进入异常处理（异常处理要在ARM状态下进行），则当异常返回时，将自动切换到Thumb状态。当处理器进行异常处理时，则从异常向量地址开始执行，将自动进入ARM状态。                         
11、堆栈指针SP使用的寄存器是R13, 链接寄存器LR使用的寄存器是LR，程序计数器PC使用的寄存器是R15。                           
12、大端格式是指数据的高字节存储在低字节地址中，低字节数据存放在高字节地址中；小端格式是指数据的高字节存储在高字节地址中，低字节数据存放在低字节地址中。           
13、关于ARM指令中的条件域。HI为无符号数大于；CC为无符号数小于；GT为带符号数大于；LE为带符号数小于或等于。                
14、SUBVS表示溢出时相减，SUBEQ表示相等时相减，SUBLS表示无符号数小于或等于时相减，SUBNE表示不相等时相减。              
15、立即寻址也称立即数寻址，这是一种特殊的寻址方式，操作数本身就在指令中给出，只要取出指令也就取到了操作数。这个操作数被称为立即数。                 
16、DCD用于分配一片连续的字存储单元并用指定的数据初始化；CODE16伪指令通知编译器，其后的指令序列为16位的Thumb指令；EQU伪指令用于为程序中的常量、标号等定义一个等效的字符名称，类似于C语言中的#define。IMPORT伪指令用于通知编译器要使用的标号在其他的源文件中定义，但要在当前源文件中引用，而且无论当前源文件是否引用该标号，该标号均会被加入到当前源文件的符号表中。                    
17、在ARM汇编语言程序中，子程序的调用一般是通过BL指令来实现的。B为（无）条件转移，BL为带链接转移，BX为带状态切换的转移，BLX为带链接和切换的转移。           
18、和0相与清零，和1相与保持不变。BIC表示位清除，EOR表示逻辑异或，ORR表示逻辑或，和0相或保持不变，和1相或置1。                      
19、嵌入式处理器都有一个系统复位引脚为nRESET或RESET，n表示低电平复位，不带n的表示高电平复位。                
20、按照AMBA规范，以ARM内核为基础的嵌入式处理芯片采用系统总线与外围总线的层次结构构建片上系统。AMBA的系统总线主要用于连接高带宽快速组件。AMBA的外围总线主要连接低带宽组件以及与外部相连的硬件组件。系统总线通过桥接器与外围总线互连。           
21、随机存取存储器包括静态和动态两种形式，即SRAM和DRAM，它们都是易失性存储器，即掉点后信息丢失。                   
22、I^2C总线可以挂接多个器件，其中主动发起数据传输操作的I2C器件是主控器件（主器件），否则它就是从器件。                      
23、USB总线（1.1和2.0）有4根信号线，采用半双工差分方式，用来传送信号并提供电源。Mini USB也提供电源。USB总线通常采用主从方式，它有一个主机，负责管理所有USB设备的连接与删除、发起与USB设备的通信等。                  
24、目前的触摸屏有两种形式，一种是电阻式触摸屏（俗称软屏），另一种是电容式触摸屏（俗称硬屏）。用专用硬笔写字的触摸屏属于电阻式，带多点触摸或滑动操作的触摸屏均属于电容式。                 
25、对于共阳极LED数码管，当输入为0时点亮，当输入为1时灭。要显示字符9，只需e和dp段灭，即e和dp段输入1。               
26、S3C2410存储器控制组件包括存储器控制器、总线控制器、外部主控器、NAND Flash控制器等。存储器控制器提供访问外部存储器所需的存储器控制信号，支持大/小端模式，地址空间共1GB（8个BANK，每个BANK大小为128MB）。以ARM芯片为核心的嵌入式系统其I/O与存储器采用统一编址方式，并不像x86那样采用的是I/O映射编址（独立编址）方式。BANK0只能是16位和32位总线宽度的访问，其他所有BANK可访问8位、16位和32位。        
27、S3C2410的GPIO端口有GPA/GPB/GPC/GPD/GPE/GPF/GPG/GPH多个并行I/O接口。  
28、基于UART可以构成RS-232接口和RS-485接口。RS-232接口标准的最长通信距离为15m，而RS-485接口标准的最长通信距离为1200m。RS-485通常用于主从式多机通信系统，采用轮询方式，由主机逐一向从机寻址，当从机地址与主机发送的地址一致时，才建立通信链接，进行有效数据通信。                         
29、μC/OS-II不支持时间片轮转调度法，因此赋给每一个任务的优先级是不相同的。μC/OS-II是抢占式实时操作系统内核且每个任务拥有自用栈。μC/OS-II属于源码公开的实时嵌入式操作系统。             
30、μC/OS-II基本不包含设备驱动程序，只是一个纯内核。μC/OS-II驱动程序属于底层，需要系统开发商自行开发。使用μC/OS-II的栈空间校验函数，可以确定每个任务到底需要多少栈空间。                   
31、OSSched（）函数是任务调度的前导函数，判断进行任务调度的三个条件是否满足。这三个条件是：（1）中断嵌套层数共享全程变量OSIntNesting=0，也就是所有的ISR已经执行完毕。（2）任务调度加锁层数共享全程变量OSLockNesting=0，也就是调度没有被禁止。调度器上锁函数OSSchedlock（）对共享变量OSLockNesting做加1操作，用于禁止任务调度，直到任务完成后，再调用给调度器开锁函数OSSchedUnlock（）对共享变量OSLockNesting做减1操作。（3）就绪表查找到的最高优先级任务的优先级比当前任务的优先级高。                  
32、OSTaskCreate()函数与任务创建相关。OSIntExit()函数为中断级的调度。OSTickISR()为时钟节拍中断服务子程序，与时间管理相关。                
33、Linux的源代码与Unix的源代码是完全不同的，尽管函数和命令的功能、处理结果、函数名称和参数十分相同，以及Unix的行命令、驱动程序和应用程序在Linux上能够运行。Unix是优秀的主流操作系统，Linux属于一种“类Unix”系统，Linux的运行效率还没有超过Unix。   
34、OS_CPU_C.C用于创建任务的自用栈空间、定义用户接口hook函数原型等。OS_CORE.C为核心调度代码，功能包括系统初始化、启动多任务调度开始运行、任务创建管理与调度、TCB初始化、就绪表初始化、ECB初始化、任务事件就绪表、空闲任务等。OS_MEM.C为内存管理，包括创建分区、获得存储块等。OS_TASK.C为任务管理，包括改变一个任务的优先级、创建或者删除一个任务、挂起一个任务、恢复一个被挂起的任务等。              
35、在μC/OS-II中，OSInit()函数先建立最初的任务就绪表，然后建立4个空白的数据链表。它们分别是任务控制块链表、事件控制块链表、标志链表和内存控制块链表。              
36、Unix、嵌入式Linux、WinCE、Mac OS、Android OS和DOS操作系统是典型的单内核操作系统。属于微内核结构的典型嵌入式操作系统有Symbian、VxWorks、QNX、μC/OS-II、iOS等。                  
37、Linux内核主要由5个子系统组成：进程调度（SCHED），内存管理（MM），虚拟文件系统（VFS），网络接口（NET），进程间通信（IPC）。            
38、IEEE的实时UNIX分委会认为实时操作系统应该具备7个特征：具有异步I/O和中断处理能力；任务切换时间和中断延迟时间确定；优先级中断和调度；抢占式调度；内存锁定；连续文件；同步。                
39、一个工程项目中至少应包含一个生成目标，ARM提供的可执行输出文件的模板包括了下面3个生成目标：Debug、Release、DebugRel。ADS1.2采用工程项目形式来管理应用程序中涉及的源文件、库文件、头文件等。工程项目中可以按照一定的逻辑关系来分组管理文件。当地址映射关系比较简单时，使用编译、连接选项来确定输入文件的连接顺序。当地址映射关系比较复杂时，使用scatter（分散加载）格式的文件来确定输入文件的连接顺序。          
40、arm-linux-gcc–S–o test.s test.c  该命令中只加入了参数-S、-o test.s，执行该命令后，编译器将连续执行预处理、编译等阶段的操作，最终生成文件名为test.s的汇编语言文件。注意，若去掉-o test.s参数，编译器也会自动生成文件名为test.s的汇编语言文件。     arm-linux-gcc–c–o test.o test.c  该命令中只加入了参数-c、-o test.o，执行该命令后，编译器将连续执行预处理、编译、汇编等阶段的操作，没有执行连接阶段的操作，最终生成文件名为test.o的目标文件。注意，若去掉-o test.o参数，编译器也会自动生成文件名为test.o的目标文件。arm-linux-gcc–o test test.c  该命令中只加入了参数-o test，而没有加入-c、-S、-E等，执行该命令后，编译器将连续执行预处理、编译、汇编、连接等阶段的操作，最终生成文件名为test的输出文件。arm-linux-gcc–g–o test test.c  该命令中加入了参数-g、-o test，执行该命令后，编译器将在生成的输出文件test中加入GDB能够使用的调试信息，使得用GDB调试时比较方便。                    
## 填空题 
41、嵌入式系统硬件部分的逻辑组成及其与外部世界的关系，硬件的主体是中央处理器和存储器，他们通过I/O接口和I/O设备与外部世界联系，并借助总线相互连接。中央处理器（CPU）由运算器、控制器、寄存器、高速缓冲存储器（Cache）等部件组成。           
42、数字图像的文件格式包括BMP，TIF（或TIEF），GIF，JPEG，PNG等，各有特点，适合不同的应用需求。JPEG是静止图像数据压缩编码的国际标准，它特别适合处理各种连续色调的彩色或灰度图像，算法复杂度适中，软硬件实现皆可，目前已在互联网和数码相机中得到广泛应用。GIF是目前互联网上广泛使用的一种图像文件格式，它的颜色数目较少（不超过256色），文件特别小，适合互联网传输。                
43、无线局域网的主要通信协议IEEE 802.11（俗称wifi）。IEEE 802.11n使用2.4GHz频段和5GHz频段，传输速度300Mbps，最高可达600Mbps，可向下兼容802.11b、802.11g。        
44、ARM处理器的指令集结构以及嵌入式Cortex系列。ARM处理器的指令集结构有两种：RISC和CISC，ARM处理器采用RISC结构。Cortex-A系列是面向高端应用的处理器核，Cortex-R系列是面向实时控制的处理器，Cortex-M系列是面向微控制器的处理器核。         
45、ARM处理器中的程序状态寄存器CPSR的相关知识。T为ARM与Thumb指令切换，T=1时执行Thumb指令，否则执行ARM指令。            
46、ORR表示逻辑或。和0相或保持不变，和1相或置1。ORR R0,R1,R2中是将R1和R2相或后赋给R0，R2保持不变。            
47、MOV R0,R1, LSR#2表示将R1中的内容右移两位后送到R0中，左端用0来填充。8800的二进制为1000100000000000，右移两位后变为0010001000000000，即为2200。R1保持不变。             
48、LDRB指令用于从存储器中将一个8位的字节数据传送到目的寄存器中，同时将寄存器的高24位清零。当程序计数器PC作为目的寄存器时，指令从存储器中读取的字数据被当作目的地址，从而可以实现程序的跳转。STR指令用于从源寄存器中将一个32位的字数据传送到存储器中。该指令在程序设计中比较常用，且寻址方式灵活多样，使用方式可参考指令LDR。       
49、嵌入式系统使用的存储器有多种类型，按照其存取特性可分为随机存取存储器（RAM）和只读存储器（ROM）；按照所处物理位置可分为片内存储器（芯片内置的存储器）和片外存储器（外部扩展的存储器）以及外部存储设备；按照存储信息的不同可分为程序存储器和数据存储器。              
50、存储器容量是指每一个存储芯片或模块能够存储的二进制位数，它以存储1位二进制位为最小单位（b），容量单位有字节（B）、千字节（KB）、兆字节（MB）、吉字节（GB）、太字节（TB）、拍字节（PB）、艾字节（EB）、泽字节（ZB）以及尧字节（YB）等。对于内存容量而言，这些容量单位之间的相互关系均以1024倍表示；对于外存容量而言，这些容量单位之间的相互关系却以1000倍表示。              
51、串行异步通信接口通用异步收发器（Universal Asynchronous Receiver/Transmitter, UART）常用于全双工串行异步通信。UART由发送器、接收器、控制单元、波特率发生器等构成。          
52、AHB（Advanced High-performance Bus，先进高性能总线）用于连接高性能系统组件或高带宽组件。APB（Advanced Peripheral Bus，先进外围总线）用于连接所有通用外设组件。             
53、电源管理模块具有正常模式（NORMAL MODE）、慢速模式（SLOW MODE）、空闲模式（IDLE MODE）和掉电模式（POWER_OFF MODE）共四种模式。慢速模式下不使用PLL时钟（MPLL关闭不使用），这样功耗降低，仅使用外部晶体或外部时钟直接提供给其他组件使用，不通过锁相环电路（低速情况无需锁相处理）。             
54、μC/OS-II的启动过程为：Bootloader执行完毕后，调用应用程序主文件中的main（）函数。main（）函数在执行过程中，除了用户函数和硬件初始化函数外，按以下次序执行3个主要的μC/OS-II函数：操作系统初始化OSInit（），任务创建OSTaskCreate（），任务调度开始OSStart（）。一旦OSStart（）函数开始执行，就标志着μC/OS-II进入了多任务调度的正常运行状态。                
55、HAL隐藏了硬件的差异性，使得操作系统在不同的硬件平台上运行时，内核的代码不需要改动，从而改善了操作系统的可移植性。               
56、μC/OS-II的五种任务状态。绝大多数情况下，μC/OS-II的每个任务都是一个无限的循环。每个任务都处在以下5种状态之一的状态下。这5种状态是休眠态、就绪态、运行态、挂起态（等待某一事件发生）和被中断态。μC/OS-II就绪表为每一个优先级的任务提供了一个位元，登记该任务是否就绪，就绪时取值为1，没有就绪时取值为0。这样，就绪位为1的所有任务构成了当前就绪任务集。                  
57、嵌入式Linux中Bootloader提供的OS装载方式。装载操作系统映像到内存，通常Bootloader程序会提供几种装载方式：从串口或者以太网装载，从非易失性存储器（主要指Flash存储器）装载。               
58、μC/OS-II中断退出函数OSIntExit()的使用。调用中断退出函数OSIntExit（）标志着中断服务子程序的终结，OsintExit（）将中断嵌套层数计数器减1。             
59、嵌入式应用程序经过交叉工具链生成映像文件之后需要下载到目标机进行调试。调试完毕后映像文件必须存储在目标机的非易失性存储器中，即要求生成软件的固化版本，烧写到目标机的ROM中。将程序代码烧写到ROM中去的专用设备和工具程序俗称“编程器”。        
60、RVDS开发工具套件中，主要包括工程管理器（IDE）、编译连接器（RVCT）、调试器（RVD）和指令集仿真器（RVISS）等。RVDS调试器支持硬件在线调试和软件仿真调试，通过它可以进行单步、断点调试，并观察程序运行中的变量、寄存器、主存储器单元等的内容，使设计者能够据此判断程序运行的状况是否正常。              
