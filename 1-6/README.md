# F103 按键双击点灯实验(进阶)
板卡：STM32F103C8T6，HSE=8 MHz，系统时钟=72 MHz
接线：PA13/SWDIO，PA14/SWCLK，GND；单一 3.3 V 供电
LED：PC0，高电平点亮
KEY；PB0，按下低电平
打开：1-6/MDK-ARM/1-6.uvprojx
构建：Keil Build，下载后复位
现象：双击LED亮，再次双击按下熄灭。