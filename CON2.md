# CON2

![CON2](./Images/CON2.png)

## PIN1,2 - VDD33_A31

接供电VDD33_A31，该供电源引自核心板上PMIC芯片S5M8767A默认关闭LDO脚VLDO24。该引脚电源输出在uBoot结束后被Linux系统内的驱动程序开启。

## PIN3 - 6260_GPIO2

开发板上通过0欧电阻R175直通HUB_CONNECT脚（CON2, PIN77）。在核心板上接4412芯片的XEINT26/KP_ROW10/ALV_DBG22/GPX3_2（G9）引脚。

