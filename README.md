# [CH564](https://github.com/SoCXin/CH564)

* [WCH](http://www.wch.cn/)：[RISC-V](https://github.com/SoCXin/RISC-V)
* [L1R3](https://github.com/SoCXin/Level): 120 MHz 

## [简介](https://github.com/SoCXin/CH564/wiki)

[CH564](https://www.wch.cn/products/CH564.html) 是一款基于青稞RISC-V内核设计的工业级微控制器。CH564内置 USBHS PHY和PD PHY，支持USB Host主机和USB Device设备功能、PDUSB及Type-C快充功能；内置以太网控制器MAC和10M/100M物理层收发器；提供了外部总线接口XBUS、8位被动并口SLV、12位模数转换ADC、多组定时器、4组UART串口、I2C接口、2个SPI接口等丰富外设资源。

``` mermaid
gantt
    title CH564 SDK
    dateFormat  YYYY-MM-DD
    section Mainline Release
    v1.0           :a1, 2024-06-01, 2024-09-30
```

### 关键特性

* 120MHz RISC-V4J
* 64/96/128KB SRAM + 192KB Flash
* 多路外部12位模数转换ADC
* 多组定时器和脉宽调制 PWM
* 4xUART：兼容16C550，通讯波特率高达12Mbps
* 1个I2C接口和2个SPI接口
* 1个8位被动并口SLV
* 1个外部总线接口XBUS
* 以太网控制器 MAC 及 10M/100M PHY
* USB2.0高速控制器及PHY
* USB PD和Type-C控制器及PHY
* 快速GPIO端口，部分耐受5V
* 封装：LQFP128、LQFP64M、QFN26C3（小封装无USBHS）

## [资源收录](https://github.com/SoCXin)

* [参考资源](src/)
* [参考文档](docs/)
* [参考工程](project/)
* [mounriver开发环境](http://www.mounriver.com/download)

## [选型建议](https://github.com/SoCXin)

[CH564](https://github.com/SoCXin/CH564) 集成了高速USB(480Mbps +PHY)，支持以太网和USB-PD。

