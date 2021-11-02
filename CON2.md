# CON2

![CON2](./Images/CON2.png)

## PIN1,2 - VDD33_A31

接供电VDD33_A31，该供电源引自核心板上PMIC芯片S5M8767A默认关闭LDO脚VLDO24。该引脚电源输出在uBoot结束后被Linux系统内的驱动程序开启。

## PIN3 - ISP_SCL

开发板上未引出。在核心板上接4412芯片的XispI2C0SCL/CAM_GPIO10/GPM4_0（AE6）引脚，同时通过1K电阻R49接到VDD18_CAM。

## PIN4 - ISP_SDA

开发板上未引出。在核心板上接4412芯片的XispI2C0SDA/CAM_GPIO11/GPM4_1（AE7）引脚，同时通过1K电阻R48接到VDD18_CAM。

## PIN5 - 6260_GPIO2

开发板上通过0欧电阻R175直通HUB_CONNECT脚（CON2, PIN77）。在核心板上接4412芯片的XEINT26/KP_ROW10/ALV_DBG22/GPX3_2（G9）引脚。

## PIN6 - GND

接地。

## PIN7 - XhdmiTX0P

开发板上接HDMI插槽CON9的TMDS_D0+脚。在核心板上接4412芯片的XhdmiTX0P（AJ20）引脚。

## PIN8 - XhdmiTX1P

开发板上接HDMI插槽CON9的TMDS_D1+脚。在核心板上接4412芯片的XhdmiTX1P（AJ21）引脚。

## PIN9 - XhdmiTX0N

开发板上接HDMI插槽CON9的TMDS_D0-脚。在核心板上接4412芯片的XhdmiTX0N（AK20）引脚。

## PIN10 - XhdmiTX1N

开发板上接HDMI插槽CON9的TMDS_D1-脚。在核心板上接4412芯片的XhdmiTX1N（AK21）引脚。

## PIN11,12 - GND

接地。

## PIN13 - XhdmiTX2P

开发板上接HDMI插槽CON9的TMDS_D2+脚。在核心板上接4412芯片的XhdmiTX2P（AJ22）引脚。

## PIN14 - XhdmiTXCP

开发板上接HDMI插槽CON9的TMDS_CLK+脚。在核心板上接4412芯片的XhdmiTXCP（AJ19）引脚。

## PIN15 - XhdmiTX2N

开发板上接HDMI插槽CON9的TMDS_D2-脚。在核心板上接4412芯片的XhdmiTX2N（AK22）引脚。

## PIN16 - XhdmiTXCN

开发板上接HDMI插槽CON9的TMDS_CLK-脚。在核心板上接4412芯片的XhdmiTXCN（AK19）引脚。

## PIN17,18 - GND

接地。

## PIN19 - I2C_SDA0

开发板上接电平转换芯片TXS0102DCU（U28），转换为HDMI_SDA信号并接HDMI插槽CON9的SDA脚。在核心板上接4412芯片的Xi2c0SDA/MIPI0_BYTE_CLK/GPD1_0（AF27）引脚，同时通过1K电阻R36接到VDDIOPERI_18。

## PIN20 - I2C_SCL0

开发板上接电平转换芯片TXS0102DCU（U28），转换为HDMI_SCL信号并接HDMI插槽CON9的SCL脚。在核心板上接4412芯片的Xi2c0SCL/MIPI0_ESC_CLK/GPD1_1（AG27）引脚，同时通过1K电阻R36接到VDDIOPERI_18。

## PIN21 - HDMI_HPD

开发板上通过带电阻三极管PDTC114YE（Q1）间接接HDMI插槽CON9的HOTPLUG脚。在核心板上接4412芯片的XEINT31/HDMI_HPD/ALV_DBG27/GPX3_7（B3）引脚。

## PIN22 - XEINT30/HDMI_CEC/ALV_DBG26

开发板上接电平转换芯片TXS0102DCU（U29），转换为CBL_CEC信号并接HDMI插槽CON9的CEC脚。在核心板上接4412芯片的XEINT30/HDMI_CEC/ALV_DBG26/GPX3_6（G6）引脚。

## PIN23 - HDMI_IIC_EN

开发板上接电平转换芯片TXS0102DCU（U28）的使能引脚OE。在核心板上接4412芯片的XGNSS_RF_RSTN/GPL0_6（AB2）引脚。

## PIN24 - XuotgVBUS

接开发板上USB OTG接口CON7的VBUS引脚。在核心板上接到4412芯片的XuotgVBUS（B8）引脚。




