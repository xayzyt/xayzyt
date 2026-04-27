<div align="center">

# 张云腾 | Embedded Software Intern

通信工程本科在读，求职方向：嵌入式软件日常实习生  
关注嵌入式系统、物联网终端通信、RTOS 多任务架构与软硬件联合调试。

[![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)](#)
[![ESP--IDF](https://img.shields.io/badge/ESP--IDF-E7352C?style=flat-square&logo=espressif&logoColor=white)](#)
[![FreeRTOS](https://img.shields.io/badge/FreeRTOS-173B6C?style=flat-square)](#)
[![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)](#)
[![LVGL](https://img.shields.io/badge/LVGL-343839?style=flat-square)](#)
[![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)](#)
[![Email](https://img.shields.io/badge/Email-15234711471%40163.com-0078D4?style=flat-square)](mailto:15234711471@163.com)

</div>

## About Me

我正在系统学习并实践嵌入式软件开发，主要围绕 **ESP32 / STM32 / CH32V** 平台做项目，熟悉从底层外设驱动、RTOS 任务拆分，到联网通信、屏幕 UI 和整机联调的完整开发流程。

- 能使用 **C** 完成嵌入式功能开发、模块封装、调试验证和问题定位。
- 熟悉 **FreeRTOS** 任务、队列、信号量、互斥锁、软件定时器和事件组等常用机制。
- 做过 **Wi-Fi、MQTT、HTTP、SNTP、Web 配网、HTTP SSE** 等联网与数据交互功能。
- 有 **LVGL、ST7789、Intel 8080 并口、DMA 刷屏** 等嵌入式图形界面开发经验。
- 能阅读原理图并配合硬件调试，完成传感器、电机、执行机构与主控逻辑的联调。

## Tech Stack

| 方向 | 关键词 |
| --- | --- |
| MCU / SoC | ESP32-S3, ESP32-P4, STM32F1, STM32G4, CH32V203 |
| RTOS / 架构 | FreeRTOS, 多任务调度, 状态机, 主从协同架构 |
| 外设驱动 | GPIO, UART, I2C, SPI, PWM, ADC, Timer |
| 物联网通信 | Wi-Fi, MQTT, HTTP, SNTP, Web 配网, HTTP SSE |
| 图形界面 | LVGL, ST7789, Intel 8080, DMA |
| 工具与数据 | ESP-IDF, Keil, STM32 HAL / 标准库, cJSON, Python 脚本, 嘉立创 EDA |

## Featured Projects

### 低空物流微港节点 | ESP32-P4 + CH32V203

面向低空物流“最后十米”建筑侧接驳场景，设计并开发 **ESP32-P4 边缘视觉主控 + CH32V203 机电执行副控** 的智能微港节点，实现无人机识别鉴权、自动接货回收、状态上报与联网扩展的闭环流程。

- 搭建主从协同架构，将边缘视觉决策与机电执行控制解耦。
- 使用 FreeRTOS 状态机组织识别、鉴权、接货、回收、关舱与异常处理流程。
- 联动步进电机、直线推杆、限位/重量/红外传感器，完成托盘伸缩、货物检测与安全闭锁。
- 设计主从通信协议和本地 UI，接入 Wi-Fi + MQTT，实现云端任务下发与节点状态同步。

### [ESP32-S3-AIDA64-Monitor](https://github.com/xayzyt/ESP32-S3-AIDA64-Monitor)

基于 ESP32-S3、ESP-IDF、FreeRTOS 与 LVGL 的桌面智能终端，集成网络时钟、实时天气、PC 硬件状态监控和手机 Web 配网。

- 移植 LVGL 图形界面，配置 ST7789 屏幕的 Intel 8080 并口与 DMA 传输。
- 实现 AP + STA 共存的网络管理模块，搭建设备端 HTTP Web 服务。
- 对接 SNTP 时间同步和天气 API，使用 cJSON 解析结构化数据。
- 通过 HTTP SSE 解析 AIDA64 数据流，将 CPU、内存、温度与占用率显示到嵌入式屏幕。

### [STM32-Smart-Car](https://github.com/xayzyt/STM32-Smart-Car)

基于 STM32 的智能小车综合实践，覆盖传感器读取、电机控制、蓝牙通信和多模式运行。

- 实现红外循迹、超声波避障/跟随、蓝牙遥控与电机驱动控制。
- 整理硬件资料、原理图/PCB、软件源码和调试记录，便于复现和面试讲解。

### [FreeRTOS_Project](https://github.com/xayzyt/FreeRTOS_Project)

记录 FreeRTOS 学习和实时系统实践，重点关注任务调度、同步机制和多任务程序结构设计。

- 覆盖任务创建、队列、信号量、互斥锁、软件定时器、事件组等基础模块。
- 以小实验方式沉淀 RTOS API 使用方法和调试思路。

## Repositories To Check First

| Repository | 面试官可以快速看到的能力 |
| --- | --- |
| [ESP32-S3-AIDA64-Monitor](https://github.com/xayzyt/ESP32-S3-AIDA64-Monitor) | ESP-IDF, FreeRTOS, LVGL, Wi-Fi, HTTP/SSE, DMA 显示驱动 |
| [STM32-Smart-Car](https://github.com/xayzyt/STM32-Smart-Car) | STM32 外设、传感器、电机控制、蓝牙通信、硬件资料整理 |
| [FreeRTOS_Project](https://github.com/xayzyt/FreeRTOS_Project) | RTOS 任务调度、同步通信、实时系统基础 |
| [Data-Structures](https://github.com/xayzyt/Data-Structures) | 数据结构与算法基础练习 |
| [C-Language-Practice](https://github.com/xayzyt/C-Language-Practice) | C 语言基础与嵌入式语法练习 |
| [Python-Practice](https://github.com/xayzyt/Python-Practice) | Python 脚本与辅助工具能力 |

## Contact

- Email: [15234711471@163.com](mailto:15234711471@163.com)
- GitHub: [github.com/xayzyt](https://github.com/xayzyt)

