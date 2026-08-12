# 张云腾 · xayzyt

**通信工程本科在读｜嵌入式软件实习生方向**

[![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)](https://en.cppreference.com/w/c)
[![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)](https://www.espressif.com/)
[![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)](https://www.st.com/)
[![FreeRTOS](https://img.shields.io/badge/FreeRTOS-173B6C?style=flat-square)](https://www.freertos.org/)
[![LVGL](https://img.shields.io/badge/LVGL-343839?style=flat-square)](https://lvgl.io/)

我主要使用 **C** 进行嵌入式开发，围绕 ESP32、STM32 和 CH32 完成过图形界面、设备通信、外设驱动与多控制器协同项目。当前重点关注 **FreeRTOS、状态机、UART 协议、传感器/执行器驱动，以及软硬件联调与问题定位**。

> Communication Engineering undergraduate seeking an embedded software internship. Focused on C firmware, ESP32/STM32/CH32, FreeRTOS, LVGL, peripheral drivers, device communication, and hardware-software integration.

## 核心能力

- **嵌入式 C / MCU**：STM32F103、ESP32-S3、ESP32-P4、CH32V203；能够完成基础驱动、功能模块、调试与联调验证。
- **RTOS 与系统组织**：FreeRTOS 任务、队列、信号量、事件组、任务通知、软件定时器；使用状态机组织设备流程。
- **外设与通信**：GPIO、UART、I2C、SPI、PWM、ADC、Timer；熟悉 CRC16、ACK/NACK、超时处理、RS485/Modbus RTU。
- **图形界面与联网**：LVGL、ST7789、8080 并口、HTTP/SSE、SoftAP + STA、SNTP、AIDA64 RemoteSensor。
- **软硬件协同**：能够阅读基础电路图，使用嘉立创 EDA 进行 PCB 绘制，并参与传感器、屏幕、摄像头与执行机构联调。

## 精选项目

### [低空物流末端智能接驳系统](https://github.com/xayzyt/Embedded_competition)

省级大创项目负责人。面向无人机末端配送场景，基于 **ESP32-P4 + CH32V203** 开发智能接驳设备：

- 使用 FreeRTOS 管理视觉、控制与通信任务，以状态机组织接驳流程；
- 设计 ESP32-P4 与 CH32V203 间 UART 自定义协议，实现帧解析、CRC16、ACK/NACK 与超时处理；
- 结合 AprilTag 的 ID、位置、距离和连续帧判断接驳条件；
- 联调 TMC2209、L298N、HX711 等模块，完成舱门、托盘动作与重量确认。

**技术栈：** `C` `ESP32-P4` `CH32V203` `FreeRTOS` `AprilTag` `UART` `CRC16`

### [ESP32-S3 桌面信息与 PC 状态监控终端](https://github.com/xayzyt/ESP32-S3-AIDA64-Monitor)

基于 **ESP32-S3 + ESP-IDF** 的桌面信息终端，通过 Wi-Fi 获取网络时间、天气与 AIDA64 主机状态，并支持 Web 配网与图形化交互：

- 使用 FreeRTOS 划分 UI、AIDA64、天气与网络任务，通过 EventGroup 管理协同；
- 使用 LVGL + esp_lcd 驱动 ST7789，基于 8080 并口完成界面刷新与触摸交互；
- 通过 HTTP/SSE 接收并解析 CPU、内存等主机状态，实时刷新监控页面；
- 实现 SoftAP + STA 配网、热点扫描、断线重连、SNTP 校时与天气同步。

**技术栈：** `C` `ESP32-S3` `ESP-IDF` `FreeRTOS` `LVGL` `HTTP/SSE` `SNTP`

### [STM32F103 工业工位环境监控终端](https://github.com/xayzyt/STM32_Industrial_Workstation_Monitor)

基于 **STM32F103** 的现场监控终端原型，完成温湿度、光照、距离与时间采集，本地 OLED 菜单交互、照明控制，并扩展 RS485/Modbus RTU 通信。

**技术栈：** `C` `STM32F103` `OLED` `BH1750` `DHT11` `HC-SR04` `DS1302` `RS485/Modbus RTU` `PWM`

## 更多实践

- [FreeRTOS_Project](https://github.com/xayzyt/FreeRTOS_Project)：STM32F103 任务、队列、信号量、事件组、软件定时器与内存管理实验
- [PID_INVERTED_PENDULUM](https://github.com/xayzyt/PID_INVERTED_PENDULUM)：位置式、增量式与积分改进 PID 控制实验
- [STM32-Smart-Car](https://github.com/xayzyt/STM32-Smart-Car)：循迹、避障、跟随与蓝牙控制实践

## 教育与荣誉

- 2023.09–2027.06｜邵阳学院｜通信工程｜本科
- 蓝桥杯嵌入式国赛三等奖
- 嵌入式芯片与系统设计竞赛中部赛区二等奖
- CET-4｜校级奖学金

## 联系我

- Email：[15234711471@163.com](mailto:15234711471@163.com)
- GitHub：[@xayzyt](https://github.com/xayzyt)
