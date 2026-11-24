# F103 2-2-1
板卡：STM32F103C8T6，HSE=8 MHz，系统时钟=72 MHz
接线：PA13/SWDIO，PA14/SWCLK，GND；单一 3.3 V ，5 V 供电，舵机单独供电
舵机：PC0，50Hz
PSC: 71
ARR:19999
CCR: CCR = 2000/180*角度+500
打开：2-2-1/MDK-ARM/2-2-1.uvprojx
构建：Keil Build，下载后复位
现象：舵机转动周期4s