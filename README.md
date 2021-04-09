# attnode_v3_micro
 MicroNode based on @Seiichiro0185's attno.de V3

A small functional LORA-Node based on the [attno.de v3](https://attno.de) and sg112a-CO<sub>2</sub>-Sensor

The RFM95w must be soldered on J1 and J2 above the ATTiny. This Node can only operated with 3.3V operating voltage, the power-connection is relized over the I²C-Haeder. The UART bus (RX/TX) is available via the pads of the Progheader.

The pin in the pinheader J2 on the antenna port of the RFM should not be applied so that you can attach a small helix directly to the RFM.

![front view](https://github.com/theArcher73/attnode_v3_micro/blob/main/kicad_project/img/front.png)

![Rear view](https://github.com/theArcher73/attnode_v3_micro/blob/main/kicad_project/img/rear.png)
