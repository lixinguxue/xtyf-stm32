# F103 2-2
板卡：STM32F103C8T6，HSE=8 MHz，系统时钟=72 MHz
接线：PA13/SWDIO，PA14/SWCLK，GND；单一 3.3 V 供电
LED：PC0，高电平点亮
PSC：719
ARR；99
CCR：每0.01s自增或自减1
打开：2-2/MDK-ARM/2-2.uvprojx
构建：Keil Build，下载后复位
现象：LED呼吸灯周期2s