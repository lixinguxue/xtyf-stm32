# F103 2-5
板卡：STM32F103C8T6，HSE=8 MHz，系统时钟=72 MHz
接线：PA13/SWDIO，PA14/SWCLK，GND；单一 3.3 V ，5 V 供电，舵机单独供电
舵机：PC1，50Hz
电位器；PA0
PSC: 71
ARR:19999
CCR: CCR = 500 + a/2，a为ADC转换后的值
打开：2-5/MDK-ARM/2-5.uvprojx
构建：Keil Build，下载后复位
现象：旋转旋钮，舵机转动。