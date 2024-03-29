# 模拟考试卷2

## 选择题       
 
1、嵌入式系统与通用计算机一样，也由硬件和软件两部分组成。硬件的主体是CPU和存储器，它们通过I/O接口和I/O设备与外部世界联系。嵌入式系统的软件配置有多种情况，有些简单，有些比较复杂；而嵌入式系统的CPU有ARM、DSP和FPGA等。            
2、数字信号处理器英文缩写为DSP，它是一种适用于数字信号处理的微处理器，它支持单指令多数据（SIMD）并行处理的指令，能显著提高音频、视频等数字信号的数据处理效率。                     
3、随着电子设计自动化水平的提高和VLSI制造技术的飞速发展，半导体加工已经从微米、亚微米进入到深亚微米的时代，单个芯片上可以集成几亿个甚至几十亿个晶体管，因而能够把计算机或其他一些电子系统的全部电路都集成在单个芯片上，这种芯片就是所谓的片上系统。SoC芯片中既包含数字电路，也可以包含模拟电路，甚至还能包含数字/模拟混合电路和射频电路。由于SoC将嵌入式系统的几乎全部功能都集成在一块芯片中，单个芯片就能实现数据的采集、转换、存储、处理和I/O等多种功能。目前，大多数32位的嵌入式处理芯片均为SoC，SoC逐渐成为集成电路设计的主流发展趋势。
4、嵌入式系统的分类有多种。按系统的软硬件技术复杂度，嵌入式系统分为低端系统、中端系统和高端系统。                      
5、集成电路根据其集成度的高低可以分为小规模（SSI）、中规模（MSI）、大规模（LSI）、超大规模（VLSI）和极大规模（ULSI）等几种。嵌入式处理芯片大多属于VLSI和ULSI。集成电路的制造大约需要几百道工序，工艺复杂且技术难度非常高，许多工序必须在恒温、恒湿、超洁净的无尘厂房内完成，生产、控制及测试设备异常昂贵。集成电路大多在硅衬底上制作而成，硅衬底是单晶硅锭经切割、研磨和抛光而成的圆形薄片。集成电路中的电路及电子元件，需反复交叉使用氧化，光刻，掺杂和互连等工序才能制成。
6、数字图像数据量计算公式，（1024×768×16/8）/5 = 0.3 MB。
7、以太网数据帧：前导码（7字节）、帧起始定界符（1字节）、目的MAC地址（6字节）、源MAC地址（6字节）、类型/长度（2字节）、数据（46~1500字节）、帧校验序列（4字节）。
8、一个A类IP地址由1字节（每个字节是8位）的网络地址和3个字节主机地址组成，网络地址的最高位必须是“0”, 即第一段数字范围为1～127。每个A类地址可连接16387064台主机，Internet有126个A类地址。
9、ARM采用RISC精简指令集，采用冯·诺依曼体系或哈佛结构；ARM的总线结构称为AMBA（先进微控器制总线结构），是ARM推出的开放式总线结构，是目前流行的一种工业标准片上结构；ARM处理器具有耗电省、功能强、成本低等特点。
10、ARM7~ARM11为经典ARM处理器；RM11以后则以Cortex命名，分为三个系列，-A，-R，-M系列，分别面向高端应用、实时控制和微控制器；其中Cortex-M 系列针对成本和功耗敏感的 MCU 和终端应用（如智能测量、人机接口设备、汽车和工业控制系统、大型家用电器、消费性产品和医疗器械）的混合信号设备进行过优化。
11、在ARM的体系结构中，处理器可以工作在3种不同的状态，①ARM状态②Thumb/Thumb-2状态③调试状态。ARM状态是ARM处理器工作于32位指令的状态，即32位状态，所有指令均为32位宽度。Thumb状态是ARM执行16位指令的状态，即16位状态。在Thumb模式下，指令代码只有16位，使代码密度变大，占用内存空间减小，提供比32位程序代码更佳的效能。ARM处理器复位后自动进入ARM状态。
12、程序状态寄存器(current program status register) CPSR在用户级编程时用于存储条件码；CPSR包含条件码标志，中断禁止位，当前处理器模式以及其他状态和控制信息。
13、小端模式，是指数据的高位保存在内存的高地址中，而数据的低位保存在内存的低地址中；本指令表示将寄存器R1的内容自动增加4，形成操作数的有效地址，从中取得32位操作数存入寄存器R0中。
14、将R0的值传送到以R1的值为地址的存储器中，故需采用寄存器间接寻址。ARM处理器将R0中一个字的数据，存入由R1指示的内存区域，则使用的指令是STR R0，[R1]。
15、使用逻辑与指令AND和0进行按位相与，可以起到清零的作用。
16、ARM处理器如果R1＝0x00000080，则指令MOV R0,R1, LSL#2执行后，R0的值为 0x00000200。本指令表示将寄存器R1的值左移2位后传送到R0。
17、LDR是加载/存储类指令，表示存储器到寄存器的数据传送；而 # 是立即数符号，表示立即数寻址。
18、ARM处理器在比较指令之后，如果要依据是否相等转移到指定地址L1，则以下指令错误的是（  ）。A) BEQ L1    B) BNE L1    C) BXEQ L1    D) BLAL L1      比较之后进行转移，属于分支程序设计。A、B、C三个选项中的指令均可表示，D项指令不存在，故本题选D。
19、嵌入式最小硬件系统一般包括嵌入式处理器、时钟电路、电源电路、复位电路、存储器和调试测试接口。
20、JTAG技术是一种嵌入式测试技术，目前大多数嵌入式CPU、DSP、FPGA器件都支持JTAG标准。JTAG标准允许多个芯片（电路）的边界扫描寄存器BSR通过JTAG接口串联在一起，实现对多个器件的测试。通过芯片的JTAG接口可以实现在线编程功能。
21、前向通道通常指的是输入接口，由模拟量输入接口和数字量输入接口组成，模拟输入接口包括传感器，信号调节电路（滤波，放大器等），A/D转换器等构成。后向通道是输出接口，由模拟量和数字量接口组成，包括D/A转换器，功率放大器，执行器等。
22、按照AMBA总线规范，以ARM内核为基础的嵌入式处理器芯片采用系统总线与外围总线两层结构的方式构建片上系统。连接到系统总线上高带宽组件主要包括：电源管理与时钟控制器、测试接口、外部存储器控制接口、DMA控制器、USB主机、中断控制器等；而C选项的RTC是与外围总线连接的硬件组件。
23、GPIO的引脚一般是多功能复用的，一般具有0态和1态和高阻状态；作为输入接口时具有缓冲功能，作为输出接口时具有锁存功能。
24、ARM处理芯片内部有多个可互联通信的组件，主要包括UART、I2C、SPI、CAN、USB、Ethernet等。
25、嵌入式系统使用的存储器按照其存取特性可分为RAM和ROM；按照其所处物理位置可分为片内存储器和片外存储器以及外部存储器；按照存储信息的类型可分为程序存储器和数据存储器；随着新技术的发展，新型的铁电存储器FRAM在嵌入式系统中得到了应用。
26、I^2C总线只有两条信号线，一条是数据线SDA，另一条是时钟线SCL，所有操作都通过这两条信号线完成。
27、ARM芯片中的UART收发信息时，可以采用FIFO模式，也可以采用普通模式；UART传送信息的格式以起始位开始，以停止位结束；UART传送信息时，一次传送的数据位可为5、6、7、8位，由编程决定；基于UART可组成RS-232接口。
28、利用嵌入式芯片的GPIO构成线性键盘时，一个按键需要占用一个GPIO引脚；采用矩阵键盘结构时，8个GPIO引脚最多能构成64个按键的键盘；采用机械式按键设计键盘时，按键按下时会产生抖动；矩阵键盘通常用行扫描法或反转法读取按键的特征值。
29、main()函数在执行过程中，除了用户函数和硬件初始化函数之外，需要按顺序执行以下三个主要的μC/OS-II函数：OSInit()；OSTaskCreate()；OSStart()。
30、任务处于休眠态，相当于该任务驻留在内存中，但还没有交给内核管理。
31、OSSched() 函数是任务调度的前导函数。
32、μC/OS-II允许中断嵌套，嵌套层数可达255层。
33、μC/OS-II能够提供周期性时钟信号（即所谓的时钟节拍），用于实现任务的正确延时和超时确认。节拍率应在每秒10次到100次之间，即10~100Hz。
34、μC/OS-II的事件控制块有4种类型，需要使用4个不同的函数来创建。4个不同的函数分别是：OSSemCreate（）、OSMutexCreate（）、OSMboxCreate（）、OSQCreate（）。
35、进程调度模块负责控制进程对CPU资源的使用，所采取的调度策略是使得各个进程能够公平合理地访问CPU，同时保证内核能及时地执行硬件操作。
36、U-Boot，全称 Universal Boot Loader，是德国DENX公司开发的，用于多重嵌入式CPU的Bootloader程序，它遵循GPL条款，源代码完全开放。从FADSROM、8xxROM、PPCBOOT逐步发展演化而来。
37、属于微内核结构的典型嵌入式操作系统有Symbian、VxWorks、QNX、μC/OS-II、iOS等。
38、VxWorks 操作系统是美国WindRiver公司于1983年设计开发的一种嵌入式实时操作系统（RTOS），是嵌入式开发环境的关键组成部分，支持基于抢占式优先级调度的任务管理。它以其良好的可靠性和卓越的实时性被广泛地应用在通信、军事、航空航天等高精尖技术及实时性要求极高的领域中。
39、RVDS支持所有ARM芯片，包括Cortex全系列，还支持其他内核的处理器，如51系列。
40、要对源程序进行调试，通常需要在GCC命令中加入参数-g。
## 填空题 

41、目前32位嵌入式处理器主要采用的是ARM内核处理器，是由英国一家专门从事RISC处理器内核设计公司设计的。
42、我国大陆地区目前广泛使用的汉字编码国家标准有GB2312和GB18030两种，常用汉字采用2个字节表示。
43、TCP/IP协议簇中的IP协议，在Internet中负责选择合适的路由，使发送的数据分组（packet）能够正确无误地按照地址找到目的计算机。
44、按向量地址从小到大排列的顺序是：复位、未定义指令UND、软件中断SWI、指令预取中止PABT、数据访问中止DABT、外部中断请求以及快速中断FIQ。
45、在ARM处理器中，R0～R15是通用寄存器，其中有两个较特殊，作为堆栈指针SP使用的寄存器是R13，作为程序链接寄存器LR使用的是R14。
46、已知ARM处理器的R1＝0x12345678, R2=0xFF00FF00，则执行指令ORR R0,R1,R2后，寄存器R0＝ 0xFF34FF78，R1＝0x12345678。  R0中是R1和R2逻辑或之后的值；而R1中的值不变。
47、ADDC是带进位加法，指令执行完后，R0中是R1和R2带进位相加之后的值；而R1中的值不变。已知ARM处理器进位标志C＝1, R1＝1000,  R2＝99, 执行指令ADDC R0，R1，R2之后，R0＝1100, R1=1000。
48、ARM处理器用一条指令完成有条件的无符号数加法运算，并更新CPSR中的状态，条件是如果相等, 要求指令执行R1＋R2，结果送R3中，则这条指令为ADDCEQ R3,R1,R2 ；如果条件是大于，要求指令执行R1－R2，结果放R3中，则该指令为SUBHIS  R3,R1,R2。
49、AMBA是ARM公司为连接ARM内核与处理器芯片中的其他各种组件而定义的总线规范，即先进的微控制器总线体系结构。
50、ARM处理器芯片内部的模拟组件包括ADC和DAC，有的还带有比较器等。这对于既需要处理数字信号又需要处理模拟信号的混合系统的设计提供了较好的解决方案。
51、目前有两种主要的闪存技术，一种是NOR Flash，其特点是以字节为单位随机存取，另一种是NAND Flash，以页（行）为单位随机存取。
52、存储器带宽计算公式：(333×32/8)×1B/s=1332 MB/S；若存储器总线采用串行总线，以10位为一个数据帧（包含一个字节的存储数据），则总线带宽=总线频率/10。
53、SPI的信号线MISO称为主机输入从机输出数据线, MOSI称为主机输出从机输入数据线。
54、响应时间（Response Time）是计算机从识别一个外部事件到做出响应的时间，其具体指标包括：中断延迟时间和任务切换时间。
55、μC/OS-II内核只提供任务调度、任务间通信与同步、任务管理、时间管理和存储管理等基本功能，资源消耗非常小。
56、系统中引导加载程序主要完成加电自检、外设存在自检、内存地址映射、初始化外围设备、内存寻址定位、加载并启动操作系统。
57、大多数Bootloader都分成两个执行阶段，依赖于CPU体系结构的代码，比如设备初始化代码等，通常都放在stage1中，且使用汇编语言来实现，以达到短小精悍的目的；而stage2则通常用C语言来实现，这样可以实现更复杂的功能，而且代码会具有更好的可读性和可移植性。
58、RTLinux基本的设计理念就是“架空”Linux内核，以便让其他实时进程能尽快地被执行。其开发者将Linux的内核代码做一些修改，而非针对实时操作系统的特性而重写Linux的内核，将Linux的任务以及Linux内核本身作为一个低优先级的任务，而实时任务作为最高优先级的任务。
59、嵌入式系统开发时，由于受到目标机资源的限制，需要建立一个宿主机与目标机组成的调试架构来完成开发工作；若目标机为裸机环境时，通常需要通过JTAG接口来完成硬件环境测试及初始软件的调试和下载。
60、基于嵌入式WEB的应用系统中，构件设计阶段需要设计支持以太网通信的电路，包括以太网控制电路及以太网驱动电路；按题中所述接法，AX88796芯片内部寄存器的读/写地址，其首地址一般是0x10000000。
## 综合题        

61、本题考查以S3C2410为背景的嵌入式应用系统开发。题中应用为机械设备的控制器系统开发。包括通用I/O口GPIO的使用及相应的初始化编程。其中，GPC和GPD作为LCD显示器接口引脚，GPE作为输入输出；基于UART的RS-232接口电路设计及相应的初始化编程设置；UART的通信控制；内部定时器和计数器的设置及使用；基于S3C2410的无操作系统的嵌入式系统如何构建其启动引导程序。

