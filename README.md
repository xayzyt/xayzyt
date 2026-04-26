# 张云腾

**求职方向：嵌入式软件日常实习生**

通信工程本科在读，关注嵌入式系统、物联网设备通信与软硬件协同调试。熟悉 C/C++ 嵌入式开发，能够完成驱动编写、模块开发、功能调试和联调验证。

## 技术方向

| 方向 | 内容 |
| --- | --- |
| 嵌入式平台 | ESP32-S3、ESP32-P4、CH32V203、STM32F1、STM32G4 |
| 开发环境 | ESP-IDF、STM32 标准库、STM32 HAL、Keil、嘉立创 EDA |
| RTOS 与架构 | FreeRTOS、多任务调度、状态机设计、主从协同架构 |
| 外设与驱动 | GPIO、UART、I2C、SPI、PWM、ADC、Timer |
| 通信与联网 | Wi-Fi、MQTT、HTTP、SNTP、HTTP SSE、Web 配网 |
| 图形界面 | LVGL、ST7789、Intel 8080 并口、DMA 传输 |
| 工具能力 | Python 脚本、cJSON 数据解析、基础 PCB 布局与电路图阅读 |

## 项目经历

### 基于 ESP32-P4 与 CH32V203 的低空物流微港节点

面向低空物流“最后十米”建筑侧接驳场景，设计并开发基于 **ESP32-P4 边缘视觉主控 + CH32V203 机电执行副控** 的智能微港节点，实现无人机识别鉴权、自动接货回收、状态上报与联网扩展的完整闭环。

- 搭建 ESP32-P4 + CH32V203 双芯协同架构，实现边缘视觉决策与机电执行控制解耦。
- 实现轻量 AI 无人机目标识别、AprilTag 视觉鉴权、距离估算与悬停稳定性判定。
- 基于 FreeRTOS 状态机打通识别、鉴权、接货、回收、关舱及异常处理流程。
- 完成步进电机、直线推杆、限位/重量/红外传感器联动控制，实现托盘伸缩、货物检测与安全闭锁。
- 设计主从通信协议与本地 UI，接入 Wi-Fi + MQTT，支持云端任务下发、节点状态同步与消息通知。

### 基于 ESP32-S3 的多功能智能桌面终端

开发集成网络时钟、实时气象站、PC 硬件性能监控与手机 Web 配网功能的物联网桌面终端。

- 基于 ESP-IDF 与 FreeRTOS 构建多任务系统，划分 UI 渲染、天气/SNTP 请求、后台配网等任务。
- 移植 LVGL 图形界面库，针对 ST7789 屏幕配置 Intel 8080 并行总线与 DMA 传输机制。
- 实现 AP + STA 共存模式的网络管理模块，在设备端搭建 HTTP 网页服务器与 WebSocket 服务。
- 集成 SNTP 对接阿里云/Apple 时间服务器，调用天气 API 并使用 cJSON 提取数据。
- 通过 HTTP SSE 配合正则表达式解析 AIDA64 数据流，实现 PC 端 CPU、内存、温度和占用率监控投屏。

## 公开仓库

- [STM32-Smart-Car](https://github.com/xayzyt/STM32-Smart-Car)：STM32 智能小车，包含循迹、避障、跟随和蓝牙控制。
- [ESP32-S3-AIDA64-Monitor](https://github.com/xayzyt/ESP32-S3-AIDA64-Monitor)：ESP32-S3 桌面监控屏，结合 LVGL、AIDA64 和 Wi-Fi。
- [Data-Structures](https://github.com/xayzyt/Data-Structures)：数据结构与算法基础练习。
- [C-Language-Practice](https://github.com/xayzyt/C-Language-Practice)：C 语言基础与嵌入式语法练习。
- [Python-Practice](https://github.com/xayzyt/Python-Practice)：Python 脚本与辅助工具练习。



## 联系方式

- Phone: 15234711471
- Email: 15234711471@163.com
