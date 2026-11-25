<div align="center">

# 张云腾 · xayzyt

### 嵌入式软件工程师 · 27 届毕业生

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) ![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white) ![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white) ![FreeRTOS](https://img.shields.io/badge/FreeRTOS-4B8BBE?style=flat-square) ![LVGL](https://img.shields.io/badge/LVGL-7344A5?style=flat-square)

</div>

## 🧩 技术方向

| 领域 | 技术 |
|:--|:--|
| **MCU / 平台** | STM32F103 · ESP32-S3 · ESP32-P4 · CH32V203 |
| **系统 / 界面** | FreeRTOS · ESP-IDF · LVGL · 状态机 · 模块化驱动 |
| **外设 / 通信** | GPIO · UART · I2C · SPI · PWM · ADC · DMA · RS485/Modbus RTU · MQTT |

## 🚀 精选项目

### 01 · [低空物流末端智能接驳系统](https://github.com/xayzyt/Embedded_competition)
**湖南省大学生创新创业训练计划省级立项项目负责人** · ESP32-P4 + CH32V203 多控制器协同设备

面向无人机末端配送场景，通过视觉识别与身份校验确认目标，控制舱门、托盘完成接驳，并使用称重模块确认货物交接。

- 使用 FreeRTOS 管理视觉、控制和通信任务，以状态机组织接驳流程；
- 设计 ESP32-P4 与 CH32V203 间 UART 自定义协议，实现帧解析、CRC16、ACK/NACK 与超时处理；
- 结合 AprilTag 的 Tag ID、位置、距离和连续帧判断接驳条件；
- 联调 TMC2209、L298N、HX711，完成舱门、托盘动作和重量确认。

`C` `ESP32-P4` `CH32V203` `FreeRTOS` `AprilTag` `UART` `CRC16`

### 02 · [ESP32-S3 桌面信息与 PC 状态监控终端](https://github.com/xayzyt/ESP32-S3-AIDA64-Monitor)
**ESP32-S3 + ESP-IDF** · 桌面信息展示、PC 状态监控与 Web 配网

- 使用 FreeRTOS 划分 UI、AIDA64、天气与网络任务，通过 EventGroup 管理任务协同；
- 使用 LVGL + esp_lcd 驱动 ST7789，基于 8080 并口完成界面刷新与触摸交互；
- 通过 HTTP/SSE 接收 AIDA64 RemoteSensor 数据，实时刷新 CPU、内存等监控信息；
- 实现 SoftAP + STA Web 配网、热点扫描、断线重连、SNTP 校时与天气同步。

`C` `ESP32-S3` `ESP-IDF` `FreeRTOS` `LVGL` `HTTP/SSE` `SNTP`

### 03 · [STM32F103 工业工位环境监控终端](https://github.com/xayzyt/STM32_Industrial_Workstation_Monitor)
**STM32F103** · 传感器采集、本地交互、照明控制与工业通信

- 驱动 BH1750、DHT11、HC-SR04、DS1302，完成环境与时间数据采集；
- 设计 OLED 多级菜单与按键交互，支持环境监测、时间配置、灯光设置和设备状态查看；
- 实现 RS485/Modbus RTU 从站通信，完成 CRC16 校验、数据读取与控制参数下发；
- 基于 TIM/PWM 实现多档照明调节与 RGB 状态指示。

`C` `STM32F103` `OLED` `BH1750` `DHT11` `HC-SR04` `RS485/Modbus RTU`

## 📂 更多实践

| 仓库 | 内容 |
| --- | --- |
| [FreeRTOS_Project](https://github.com/xayzyt/FreeRTOS_Project) | STM32F103 任务、队列、信号量、事件组、软件定时器与内存管理实验 |
| [PID_INVERTED_PENDULUM](https://github.com/xayzyt/PID_INVERTED_PENDULUM) | 位置式、增量式与积分改进 PID 控制实验 |
| [STM32-Smart-Car](https://github.com/xayzyt/STM32-Smart-Car) | 循迹、避障、跟随与蓝牙控制实践 |

## 📫 联系

欢迎交流嵌入式开发与项目实践。

[Email](mailto:15234711471@163.com) · [GitHub](https://github.com/xayzyt)
