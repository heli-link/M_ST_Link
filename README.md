# Helocobic-energy

## 心血来潮，**突然想做一下稚晖君的小电视**

### 文件结构

- 1、Frimware 
   - SCH&PCB
- 2、Code
     - VSSTUDIO可运行的LVGL模拟器 + STM32F411 LVGL demo
- 3、Out 
     - Model
     - Picture
     - PDF
- 4、Other
     - Material - 资料

### 设计

稚晖君小电视

##### 方案:

| 芯片        | 备注                         |
| ----------- | ---------------------------- |
| Stm32F411   | 主控                         |
| ESP32-WROOM | 网络，双核240M，双模，体积小 |
| CP2102      | usb转串口                    |
| MPU6050     | 姿态传感器                   |
| TF          | 小                           |
| 2.4 寸LCD   | ST7789，FPC连接              |

PCB&SCH：

> 原理图风格参照稚晖君，cadence设计，Allegro布线，四层板，规格25*27mm

Code:

> LVGL移植到STM32F411的Demo，LCD是2.4寸7789驱动，已调通
>
> LVGL VS模拟器工程，已调通

##### Ptcture:

SCH:

> <img style="width:70%;" src="https://s2.loli.net/2022/04/29/Fhu1aYspSW5lCEO.png" />

Renden:

> <img style="width:40%;" src="https://s2.loli.net/2022/04/29/AGJHrkendxBR7ym.png" />
>
> 

<img style="width:40%;" src="https://s2.loli.net/2022/04/29/VJ123aAxlCBbD7R.png" />

实物

> <img style="width:40%;" src="https://s2.loli.net/2022/04/29/xLOTlMfXD1Ia4yR.jpg" />



<img style="width:40%;" src="https://s2.loli.net/2022/04/29/v3iUnk4SjKqXzNc.jpg" />

### 资料

github: 由于空间限制,完整资料在网盘

 https://github.com/heli-link/Helocobic-energy 

csdn: https://download.csdn.net/download/qq_42733641/85072280 PCB&SCH,渲染图，LVGL资料，正点原子手把手LVGL，VStudio编译完成的工程（2019），硬件测试代码，E32等等所有资料和文件

### 其他

> 半成品，芯片焊接是个坑，待后续吧
