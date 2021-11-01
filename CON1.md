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

## PIN23 - Xmmc2CMD

接开发板上TF卡槽J1的CMD（命令）引脚，在核心板上接到4412芯片的Xmmc2CMD/GPK2_1（J4）引脚。

## PIN24 - GND

接地。

## PIN25 - Xmmc2DATA2

接开发板上TF卡槽J1的DAT2（数据线2）引脚，在核心板上接到4412芯片的Xmmc2DATA2/GPK2_5（K4）引脚。

## PIN26 - Xmmc2CLK

接开发板上TF卡槽J1的CLK（时钟）引脚，在核心板上接到4412芯片的Xmmc2CLK/GPK2_0（N4）引脚。

## PIN27 - Xmmc2DATA3

接开发板上TF卡槽J1的CD/DAT3（数据线3）引脚，在核心板上接到4412芯片的Xmmc2DATA3/GPK2_6（N5）引脚。

## PIN28 - Xmmc2DATA0

接开发板上TF卡槽J1的DAT0（数据线0）引脚，在核心板上接到4412芯片的Xmmc2DATA0/GPK2_3（J5）引脚。

## PIN29 - GND

接地。

## PIN30 - Xmmc2DATA1

接开发板上TF卡槽J1的DAT1（数据线1）引脚，在核心板上接到4412芯片的Xmmc2DATA1/GPK2_4（K5）引脚。

## PIN31 - VDD_TF

TF卡槽供电。

## PIN32 - XEINT7/GPX0_7

接开发板上TF卡槽J1的SW2引脚，在核心板上接到4412芯片的XEINT7/ALV_DBG3/GPX0_7（D5）引脚。

## PIN33 - VDD18_A31

接开发板Wi-Fi连接器座子J40并引出，在核心板上从PMIC芯片S5M8767A的VLDO25（D12）引脚引出。

## PIN34 - BT_RST

开发板上未引出，在核心板上接到4412芯片的Xi2s0SDO_2/ST_INT/GPZ6（Y1）引脚。

考虑到与Wi-Fi相关功能引脚共同编组，推测为蓝牙模块（Bluetooth, BT）相关。

## PIN35 - WIFI_WOW

接开发板Wi-Fi连接器座子J40并引出，在核心板上接到4412芯片的XEINT12/KP_COL4/ALV_DBG8/GPX1_4（H7）引脚。

## PIN36 - WIFI_PWDN

接开发板Wi-Fi连接器座子J40并引出，在核心板上接到4412芯片的Xi2s0SDO_1/ST_TICK/GPZ5（W4）引脚。

## PIN37 - WIFI_CLK

接开发板Wi-Fi连接器座子J40并引出，在核心板上接到4412芯片的Xmmc3CLK/GPK3_0（L6）引脚。

## PIN38 - WIFI_CMD

接开发板Wi-Fi连接器座子J40并引出，在核心板上接到4412芯片的Xmmc3CMD/GPK3_1（N6）引脚。

## PIN39 - GND

接地。

## PIN40 - WIFI_D1

接开发板Wi-Fi连接器座子J40并引出，在核心板上接到4412芯片的Xmmc3DATA1/SD_2_DATA5/GPK3_4（M7）引脚。

## PIN41 - WIFI_D0

接开发板Wi-Fi连接器座子J40并引出，在核心板上接到4412芯片的Xmmc3DATA0/SD_2_DATA4/GPK3_3（M6）引脚。

## PIN42 - WIFI_D3

接开发板Wi-Fi连接器座子J40并引出，在核心板上接到4412芯片的Xmmc3DATA3/SD_2_DATA7/GPK3_6（M5）引脚。

## PIN43 - WIFI_D2

接开发板Wi-Fi连接器座子J40并引出，在核心板上接到4412芯片的Xmmc3DATA2/SD_2_DATA6/GPK3_5（N7）引脚。

## PIN44 - XuRXD0

接开发板Wi-Fi连接器座子J40并引出，在核心板上接到4412芯片的XuTXD0/GPA0_1（AE25）引脚。

## PIN45 - XuTXD0

接开发板Wi-Fi连接器座子J40并引出，在核心板上接到4412芯片的XuRXD0/GPA0_0（AD22）引脚。

## PIN46 - XuCTSn0

接开发板Wi-Fi连接器座子J40并引出，在核心板上接到4412芯片的XuRTSn0/GPA0_3（AF23）引脚。

## PIN47 - XuRTSn0

接开发板Wi-Fi连接器座子J40并引出，在核心板上接到4412芯片的XuCTSn0/GPA0_2（AF25）引脚。

## PIN48 - XEINT18/KP_ROW2/ALV_DBG14

接开发板上音频模块WM8960GEFL（U1，手册描述为“立体声编解码器与1W立体声D类扬声器驱动器和耳机驱动器的便携式音频应用”）的ADCLRC/GPIO1（手册描述为音频接口ADC左右/时钟或GPIO1）引脚。

开发板上CON2_2_54P/NC（J5）的2号脚使用了该引脚。

在核心板上接到4412芯片的XEINT18/KP_ROW2/ALV_DBG14/GPX2_2（G5）引脚。

