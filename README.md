# 2108
韦东山嵌入式Linux全新系列教程之驱动大全(基于STM32MP157开发板)
### 微:NoBug1024 


课程介绍：

嵌入式 Linux是嵌入式操作系统的一个新成员，其最大的特点是源代码公开并且遵循GPL协议，已成为研究热点。正在开发的嵌入式系统中，有近50%的项目选择Linux作为嵌入式操作系统。

嵌入式linux 是将日益流行的Linux操作系统进行裁剪修改，使之能在嵌入式计算机系统上运行的一种操作系统。嵌入式linux既继承了Internet上无限的开放源代码资源，又具有嵌入式操作系统的特性。

嵌入式Linux的特点是版权费免费;购买费用媒介成本技术支持全世界的自由软件开发者提供支持网络特性免费，而且性能优异，软件移植容易，代码开放，有许多应用软件支持，应用产品开发周期短，新产品上市迅速，因为有许多公开的代码可以参考和移植，实时性能RT_Linux Hardhat Linux 等嵌入式Linux支持，实时性能稳定性好安全性好。


〖课程目录〗:

- ├──01-【导学】视频介绍与资料下载  
- |   ├──01-01_视频介绍.mp4  11.91M
- |   └──02-02_视频学习与资料下载.mp4  60.50M
- ├──02-同步与互斥  
- |   ├──01-1-1_内联汇编.mp4  371.50M
- |   ├──02-1-2_同步与互斥的失败例子.mp4  112.13M
- |   ├──03-1-3_原子操作的实现原理与使用.mp4  303.73M
- |   ├──04-1-4_Linux锁的介绍与使用_.mp4  44.39M
- |   ├──05-1-5_自旋锁spinlock的实现_.mp4  53.25M
- |   ├──06-1-6_信号量semaphore的实现_.mp4  19.05M
- |   └──07-1-7_互斥量mutex的实现_.mp4  58.95M
- ├──03-LCD驱动_基于STM32MP157  
- |   ├──01-3-0_LCD视频介绍.mp4  9.41M
- |   ├──02-3-1_单片机_Linux下不同接口的LCD硬件操作原理.mp4  144.74M
- |   ├──03-3-2_Framebuffer驱动程序框架.mp4  251.52M
- |   ├──04-3-3_编程_写出框架_.mp4  91.96M
- |   ├──05-3-4_编程_最简单的LCD驱动_基于QEMU_.mp4  33.34M
- |   ├──06-3-5_上机实验_基于QEMU_.mp4  112.59M
- |   ├──07-3-6_结合APP分析LCD驱动程序_.mp4  60.58M
- |   ├──08-3-7_硬件_8080接口LCD时序分析_.mp4  60.06M
- |   ├──09-3-8_硬件_TFT-RGB接口LCD时序分析_.mp4  56.47M
- |   ├──10-3-9_硬件_STM32MP157的LCD控制器.mp4  295.36M
- |   ├──11-3-10_分析内核自带的LCD驱动程序_基于STM32MP157_.mp4  1.75M
- |   ├──12-3-11_编程_LCD驱动程序框架_使用设备树_.mp4  1.75M
- |   ├──13-3-12_编程_引脚配置_基于STM32MP157_.mp4  122.45M
- |   ├──14-3-13_编程_时钟配置_基于STM32MP157_.mp4  45.24M
- |   ├──15-3-14_编程_LCD控制器配置之获得LCD参数_通用_.mp4  75.04M
- |   ├──16-3-15_编程_配置LCD控制器之寄存器操作_基于STM32MP157.mp4  662.68M
- |   ├──17-3-16_上机实验_基于STM32MP157.mp4  546.04M
- |   ├──18-3-17_单Buffer的缺点与改进方法_.mp4  41.00M
- |   └──19-3-18_STM32MP157内核自带的LCD驱动不支持多buffer_.mp4  51.69M
- ├──04-I2C子系统_基于STM32MP157  
- |   ├──01-4-1_I2C视频介绍.mp4  89.83M
- |   ├──02-4-2_I2C协议.mp4  237.35M
- |   ├──03-4-3_SMBus协议.mp4  240.01M
- |   ├──04-4-4_I2C系统的重要结构体.mp4  183.44M
- |   ├──05-4-5_无需编写驱动直接访问设备_I2C-Tools介绍.mp4  492.10M
- |   ├──06-4-6_编写APP直接访问EEPROM.mp4  617.11M
- |   ├──07-4-7_通用驱动i2c-dev分析_.mp4  53.49M
- |   ├──08-4-8_I2C系统驱动程序模型_.mp4  78.18M
- |   ├──09-4-9_编写设备驱动之i2c_driver_.mp4  85.27M
- |   ├──10-4-10_编写设备驱动之i2c_client.mp4  646.41M
- |   ├──11-4-11_I2C_Adapter驱动框架讲解与编写.mp4  438.17M
- |   ├──12-4-12_完善虚拟的I2C_Adapter驱动并模拟EEPROM.mp4  369.36M
- |   ├──13-4-13_使用GPIO模拟I2C的驱动程序分析.mp4  386.73M
- |   ├──14-4-14_使用GPIO操作I2C设备_基于STM32MP157.mp4  217.66M
- |   └──15-4-15_具体芯片的I2C_Adapter驱动分析.mp4  477.34M
- ├──05-Input子系统_基于STM32MP157  
- |   ├──01-5-1_Input子系统视频介绍.mp4  57.93M
- |   ├──02-5-2_先学习输入系统应用编程.mp4  72.92M
- |   ├──03-APP_01_输入系统框架及调试.mp4  196.72M
- |   ├──04-APP_02_现场编程读取获取输入设备信息_.mp4  78.30M
- |   ├──05-APP_03_查询_休眠唤醒_方式读取输入数据_.mp4  34.46M
- |   ├──06-APP_04_POLL_SELECT_方式读取输入数据.mp4  107.02M
- |   ├──07-APP_05_异步通知方式读取输入数据_.mp4  46.29M
- |   ├──08-APP_06_电阻屏和电容屏_.mp4  64.82M
- |   ├──09-APP_07_tslib框架分析_.mp4  60.21M
- |   ├──10-APP_08_tslib交叉编译与测试_.mp4  74.82M
- |   ├──11-APP_09_编写基于tslib的测试程序_.mp4  78.63M
- |   ├──12-DRV_01_Input子系统框架详解_.mp4  153.98M
- |   ├──13-DRV_02_编写input_dev驱动框架_.mp4  102.82M
- |   ├──14-DRV_03_编写最简单的触摸屏驱动程序之IRQ_基于QEMU_.mp4  120.63M
- |   ├──15-DRV_04_编写最简单的触摸屏驱动程序之完善_基于QEMU_.mp4  115.44M
- |   ├──16-DRV_05_GPIO按键驱动分析与使用_.mp4  95.11M
- |   ├──17-DRV_06_I2C接口触摸屏驱动分析_.mp4  37.26M
- |   └──18-DRV_07_UInput分析_用户态创建input_dev_.mp4  68.71M
- ├──06-Pinctrl子系统_基于STM32MP157  
- |   ├──01-01_Pinctrl子系统视频介绍.mp4  66.14M
- |   ├──02-02_使用Pinctrl要掌握的重要概念.mp4  249.52M
- |   ├──03-03_Pinctrl子系统使用示例_基于STM32MP157.mp4  237.79M
- |   ├──04-04_Pinctrl子系统主要数据结构_.mp4  122.95M
- |   ├──05-05_Pincontroller构造过程情景分析_基于STM32MP157_.mp4  130.32M
- |   ├──06-06_client端使用pinctrl过程的情景分析_基于STM32MP157.mp4  843.69M
- |   ├──07-07_编写虚拟的Pinctrl驱动程序之实现框架_.mp4  65.93M
- |   ├──08-08_编写虚拟的Pinctrl驱动程序之设置pinctrl_desc_.mp4  114.42M
- |   ├──09-09_编写虚拟的Pinctrl驱动程序之处理设备树_.mp4  66.46M
- |   └──10-10_调试虚拟的Pinctrl驱动程序_.mp4  104.19M
- ├──07-GPIO子系统_基于STM32MP157  
- |   ├──01-01_GPIO子系统视频介绍_.mp4  16.67M
- |   ├──02-02_使用GPIO子系统要掌握的重要概念_.mp4  43.09M
- |   ├──03-03_基于GPIO子系统的LED驱动程序_.mp4  51.19M
- |   ├──04-04_在100ASK_STM32MP157上机实验_.mp4  76.87M
- |   ├──05-05_GPIO子系统层次与数据结构_.mp4  63.10M
- |   ├──06-06_STM32MP157的GPIO驱动源码分析_.mp4  63.89M
- |   ├──07-07_编写一个虚拟GPIO控制器的驱动程序_.mp4  64.31M
- |   ├──08-08_调试与使用虚拟的GPIO控制器_.mp4  69.09M
- |   ├──09-09_GPIO子系统与Pinctrl子系统的交互_.mp4  66.27M
- |   ├──10-10_编程_GPIO使用Pinctrl_.mp4  79.93M
- |   └──11-11_GPIO子系统的sysfs接口_.mp4  20.40M
- ├──08-Interrupt子系统_基于STM32MP157  
- ├──09-UART串口子系统_基于STM32MP157  
- ├──10-PCI和PCIe子系统  
- ├──11-SPI子系统  
- └──12-USB驱动专题  
