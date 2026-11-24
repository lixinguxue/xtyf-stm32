# F103 2-1
板卡：STM32F103C8T6，HSE=8 MHz，系统时钟=72 MHz
接线：PA13/SWDIO，PA14/SWCLK，GND；单一 3.3 V 供电
LED：PC0，高电平点亮
KEY；PB0，按下低电平
打开：2-1/MDK-ARM/2-1.uvprojx
构建：Keil Build，下载后复位
现象：按下来管LED亮，再次按下熄灭，长按5Hz闪烁。