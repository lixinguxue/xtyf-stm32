# F103 点灯实验
板卡：STM32F103C8T6，HSE=8 MHz，系统时钟=72 MHz
接线：PA13/SWDIO，PA14/SWCLK，GND；单一 3.3 V 供电
LED：PC0，高电平点亮
打开：1-1/MDK-ARM/1-1.uvprojx
构建：Keil Build，下载后复位
现象：LED 亮 500 ms、灭 500 ms