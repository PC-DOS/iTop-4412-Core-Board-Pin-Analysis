# CON3

![CON3](./Images/CON3.png)

## PIN1,3,5 - VDD1V8_EXT

接供电VDD1V8_EXT，在核心板上引自VDDIOPERI_18，该供电源引自核心板上PMIC芯片S5M8767A默认常开LDO脚VLDO12。

开发板上AD转换测试用滑动变阻器R24、板载按键（音量控制、返回、休眠、菜单）、GPIO座子J38（引出脚）、UART+KEYPAD座子J41（引出脚）、电平转换芯片74ALVC164245DGG（U9）A侧参考电平、TF卡槽J1引脚上拉电平、音频芯片WM8960GEFL（U10）数字供电脚（DCVDD/DBVDD）、XEINT18/KP_ROW2/ALV_DBG14引脚上拉电平、电平转换芯片TXS0102DCU（U17、U28、U29）A侧参考电平、RGB-LVDS转换芯片GM8285C（U12）的并行数据时钟采样边沿选择端CLKSEL上拉电平及芯片供电（IOVCC1、IOVCC2）、JTAG座子（引出脚/引脚上拉电平）、HDMI座子CON9热插拔信号端（HOTPLUG）上拉电平、启动模式（OM）选择拨码开关上拉电平等均使用了这个电平。

## PIN2,4 - VDD28_AF

接供电VDD28_AF，该供电源引自核心板上PMIC芯片S5M8767A默认关闭LDO脚VLDO21。该引脚电源输出在uBoot结束后被Linux系统内的驱动程序开启。

## PIN6,8 - VDD18_CAM

接供电VDD18_CAM，该供电源引自核心板上PMIC芯片S5M8767A默认关闭LDO脚VLDO25。该引脚电源输出在uBoot结束后被Linux系统内的驱动程序开启。

## PIN7,9 - VDD12_5M

接供电VDD12_5M，该供电源引自核心板上PMIC芯片S5M8767A降压变换（Buck）回路FB6、SW6。

## PIN10,12 - VDD28_CAM

接供电VDD28_CAM，该供电源引自核心板上PMIC芯片S5M8767A默认关闭LDO脚VLDO20。该引脚电源输出在uBoot结束后被Linux系统内的驱动程序开启。



