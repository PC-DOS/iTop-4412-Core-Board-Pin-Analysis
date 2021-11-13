# CON4

![CON4](./Images/CON4.png)

## PIN1,2 - DC33V

接供电DC33V，在核心板上标为VDDIOPERI_28。该供电源引自核心板上PMIC芯片S5M8767A默认关闭LDO脚VLDO18。该引脚电源输出在uBoot结束后被Linux系统内的驱动程序开启。

300 mA，2.8V供电脚。

开发板上GPIO座子J38（引出脚）、电池模块（接V_BKCOIN）、TTL电平转换芯片MAX3232CSE（U4）、板载USB以太网卡DM9621ANP（U8）、电平转换芯片74ALVC164245DGG（U9）、音频芯片WM8960GEFL（U10）、LVDS发送器GM8285C（U12）、电平转换芯片TXS0102DCU（U29）等作为数字电源（VCC）使用或引出了该供电。

## PIN3,4 - GND

接地。

## PIN5 - XPWMTOUT1

经开发板电平转换芯片74ALVC164245DGG（U9）转换为BUF_XPWMTOUT1信号后接HDMI-LVDS接口CON17、LVDS接口J42、4.3寸RGB-LCD座子CN1、MIPI接口J9。在核心板上接4412芯片的XpwmTOUT1/LCD_PWM/GPD0_1（AD24）引脚。

显示器PWM信号输出引脚。

## PIN6 - GPX0_0

开发板上接4.3寸RGB-LCD座子CN1。在核心板上接4412芯片的XEINT0/AUD_TCK/GNSS_TCK/ALV_TCK/GPX0_0（F4）引脚。

## PIN7 - GPC1_1

接开发板Wi-Fi座子J40并引出（和被NC电阻R28断开的WIFI_PWDN共用引脚），并经开发板电平转换芯片74ALVC164245DGG（U9）转换为BUF_GPC1_1信号后接GPIO座子J38。在核心板上接4412芯片的Xi2s2CDCLK/PCM_2_EXTCLK/SPDIF_EXTCLK/SPI_2_CLK/GPC1_1（AH25）引脚。

## PIN8 - W_PMU_EN（核心板上标注为GPC1_0）

接开发板Wi-Fi座子J40并引出。在核心板上接4412芯片的Xi2s2SCLK/PCM_2_SCLK/SPDIF_0_OUT/GPC1_0（AH24）引脚。

## PIN9 - XOM2

开发板上接启动模式（OM）选择拨码开关SW2。在核心板上接4412芯片的XOM2（G1）引脚。

## PIN10 - XOM5

开发板上接启动模式（OM）选择拨码开关SW2。在核心板上接4412芯片的XOM5（G2）引脚。

## PIN11 - XOM3

开发板上接启动模式（OM）选择拨码开关SW2。在核心板上接4412芯片的XOM3（G3）引脚。

## PIN12 - XjTMS

接开发板JTAG座子CON16并引出。在核心板上接4412芯片的XjTMS/ETC0_1（AE2）引脚。

JTAG测试模式选择（TMS）引脚。

## PIN13 - XjTCK

接开发板JTAG座子CON16并引出。在核心板上接4412芯片的XjTCK/ETC0_2（AE3）引脚。

JTAG测试时钟输入（TCK）引脚。

## PIN14 - XjTDI

接开发板JTAG座子CON16并引出。在核心板上接4412芯片的XjTDI/ETC0_3（AD1）引脚。

JTAG测试数据输入（TDI）引脚。

## PIN15 - XjTDO

接开发板JTAG座子CON16并引出。在核心板上接4412芯片的XjTDO/ETC0_4（AD2）引脚。

JTAG测试数据输出（TDO）引脚。

## PIN16 - XEINT1_BAK

接开发板上GPIO座子J38并引出。在核心板上接4412芯片的XEINT1/AUD_TMS/GNSS_TMS/ALV_TMS/GPX0_1（E5）引脚。

## PIN17 - XjTRSTn

接开发板JTAG座子CON16并引出。在核心板上接4412芯片的XjTRSTn/ETC0_0（AD5）引脚。

JTAG测试复位（TRST）引脚。

## PIN18 - XEINT6

开发板上接启动模式（OM）选择拨码开关SW2。在核心板上接4412芯片的XEINT6/ALV_DBG2/GPX0_6（D3）引脚。

## PIN19 - XispSPICSn

开发板上未引出。在核心板上接4412芯片的XispSPICSn/CAM_GPIO15/GPM4_5（AG2）引脚。

## PIN20 - GND

接地。







