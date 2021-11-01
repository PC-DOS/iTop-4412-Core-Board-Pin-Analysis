# CON1

![CON1](/Images/CON1.png)

## PIN1,2,3,4,5,6 - VSYS_K

接电源VSYS_KEY，其中，1、3、5脚在开发板上有0.1 uF电容对地滤波，2、4、6脚在开发板上由0.1 uF、22 uF电容并联对地滤波。

## PIN7,8 - GND

接地。

## PIN9 - XUHOSTDATA1_EXT

接核心板上USB3503A主控（上游USB HSIC（High-Speed Inter-Chip） - 下游USB链路主控），使用R106号NC电阻和引自4412芯片E8脚XUHOSTDATA1（该引脚从4412芯片的USB HSIC 1引出）的数据链路连接，在USB3503A主控芯片上汇入到DATA（HSIC数据）引脚。

开发板上该引脚未引出。

由于该线路被NC电阻（可能未安装的电阻）断开，推测该引脚用于连接外部的HSIC控制器。

## PIN10 - XUHOSTSTROBE1_EXT

接核心板上USB3503A主控（上游USB HSIC（High-Speed Inter-Chip） - 下游USB链路主控），使用R105号NC电阻和引自4412芯片D8脚XUHOSTSTROBE1（该引脚从4412芯片的USB HSIC 1引出）的数据链路连接，在USB3503A主控芯片上汇入到STROBE（HSIC选通）引脚。

开发板上该引脚未引出。

由于该线路被NC电阻（可能未安装的电阻）断开，推测该引脚用于连接外部的HSIC控制器。

## PIN11 - MD_USBDP

开发板上USB（Host模式）接口CON15的数据正（D+）引脚，在核心板上接到USB3503A的USBDN1_DP（A1）引脚。

## PIN12 - XuotgID

接开发板上USB OTG接口CON7的ID引脚，在核心板上接到4412芯片的XuotgID引脚（D9）。

## PIN13 - MD_USBDN

开发板上USB（Host模式）接口CON15的数据负（D-）引脚，在核心板上接到USB3503A的USBDN1_DM（B1）引脚。

## PIN14 - XuotgDP

接开发板上USB OTG接口CON7的D+引脚，在核心板上接到4412芯片的XuotgDP引脚（A9）。

## PIN15 - GND

接地。

## PIN16 - XuotgDM

接开发板上USB OTG接口CON7的D-引脚，在核心板上接到4412芯片的XuotgDM引脚（A8）。

## PIN17 - UH_DP3

开发板上USB（Host模式）接口CON14的数据正（D+）引脚，在核心板上接到USB3503A的USBDN3_DP（C1）引脚。

## PIN18 - GND

接地。

## PIN19 - UH_DM3

开发板上USB（Host模式）接口CON14的数据负（D-）引脚，在核心板上接到USB3503A的USBDN3_DM（D1）引脚。

## PIN20 - UH_DP2

接开发板上百兆以太网芯片DM9621ANP的DP引脚，在核心板上接到USB3503A的USBDN2_DP（C2）引脚。

## PIN21 - GND

接地。

## PIN22 - UH_DM2

接开发板上百兆以太网芯片DM9621ANP的DM引脚，在核心板上接到USB3503A的USBDN2_DM（D2）引脚。