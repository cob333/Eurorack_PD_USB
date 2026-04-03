# Eurorack PD USB 电源模块

这是一个面向 Eurorack 系统的 USB-C PD 供电电源模块，旨在 **PD 3.0 20V 输入**下输出 **+12V、-12V、+5V** 三路电源轨。

## 预览

| 正面 | 背面 |
| --- | --- |
| ![Eurorack PD USB 正面](images/Eurorack_PD_USB_Front.png) | ![Eurorack PD USB 背面](images/Eurorack_PD_USB_Back.png) |


## 规格参数

| 项目 | 参数 |
| --- | --- |
| 输入接口 | USB-C |
| 输入协议 | USB Power Delivery 3.0 |
| 输入电压档位 | 20V |
| 输出电源轨 | +12V, -12V, +5V |
| 估计输出电流 | +12V / 1.5A, -12V / 1.5A, +5V / 1.5A |

> 输出电流为估计值，实际能力会受到 DC-DC 转换效率、散热条件、PD 适配器和线缆规格等因素影响。

## 文件说明

| 文件 | 说明 |
| --- | --- |
| `images/Eurorack_PD_USB_Front.png` | PCB 正面渲染图 |
| `images/Eurorack_PD_USB_Back.png` | PCB 背面渲染图 |
| `BOM.xlsx` | 物料清单 |
| `Gerber.zip` | PCB 生产用 Gerber 文件 |

## 使用注意事项

1. 请使用支持 **20V PD 输出**且功率余量足够的 USB-C PD 适配器。
2. 请使用满足功率要求的 USB-C 线缆，必要时使用带 E-Marker 的线缆。
3. 接入 Eurorack 模块前，请先用万用表确认 **+12V / -12V / +5V** 电压、极性和纹波情况。
4. 建议先轻载测试，再逐步增加负载，并观察电源芯片和板上器件温升。

## 免责声明

该项目目前**尚未经过实际硬件测试验证**，现阶段为**未测试版本**。请自行承担制作和使用风险，并在连接任何 Eurorack 模块前先完成充分测试。

## 许可证

本项目采用 [MIT License](LICENSE) 开源协议。
