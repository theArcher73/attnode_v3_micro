# attnode_v3_micro
 MicroNode based on @Seiichiro0185's attno.de V3

A small functional LORA-Node based on the [attno.de v3](https://attno.de) and sg112a-CO<sub>2</sub>-Sensor

The RFM95w must be soldered with 2 2mm Pin-Haeder above the ATTiny. This Node can only operated with 3.3V operating voltage, the power-connection is relized over the I²C-Haeder. The UART bus (RX/TX) is available via the pads of the Progheader.

Update 26.05.2021 moved the LED to the corner and use a LED with lateral light beam + PCB labeling cleaned.

The right pin for the antenna is marked with an *A*

The pin in the pinheader on the antenna port of the RFM should not be applied so that you can attach a small helix directly to the RFM.


 front View | rear view
 ---------- | -----------
![front view](https://github.com/theArcher73/attnode_v3_micro/blob/main/kicad_project/img/front.png) | ![Rear view](https://github.com/theArcher73/attnode_v3_micro/blob/main/kicad_project/img/rear.png)
![front view](https://github.com/theArcher73/attnode_v3_micro/blob/main/kicad_project/img/front_1.png) | ![Rear view](https://github.com/theArcher73/attnode_v3_micro/blob/main/kicad_project/img/rear_1.png)

![front_view](https://github.com/theArcher73/attnode_v3_micro/blob/main/kicad_project/img/ima_0d42fd3.jpeg)

## Thanks & Acknowledgements:

    the [attno.de project](https://attno.de) as the technological basis for this project

## Disclaimer

The documentation of the attnode_v3_micro is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
