# CON4

![CON4](./Images/CON4.png)

## PIN1,2 - DC33V

接供电DC33V，在核心板上标为VDDIOPERI_28。该供电源引自核心板上PMIC芯片S5M8767A默认关闭LDO脚VLDO18。该引脚电源输出在uBoot结束后被Linux系统内的驱动程序开启。

300 mA，2.8V供电脚。

开发板上GPIO座子J38（引出脚）、电池模块（接V_BKCOIN）、TTL电平转换芯片MAX3232CSE（U4）、板载USB以太网卡DM9621ANP（U8）、电平转换芯片74ALVC164245DGG（U9）、音频芯片WM8960GEFL（U10）、LVDS发送器GM8285C（U12）、电平转换芯片TXS0102DCU（U29）等作为数字电源（VCC）使用或引出了该供电。

## PIN3,4 - GND

接地。







