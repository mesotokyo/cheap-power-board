Cheap Power Board - Power Supply Board for Eurorack Modular
===========================================================

Cheap, compact power supply board for Eurorack modular.

 * INPUT: DC 15V
 * OUTPUT: DC +12V, -12V, +5V

This schematic and PCB data uses mst-kicad-lib: https://github.com/mesotokyo/mst-kicad-lib

![schematic image](https://github.com/mesotokyo/cheap-power-board/raw/master/figs/schematic.png "schematic image")
![PCB image](https://github.com/mesotokyo/cheap-power-board/raw/master/figs/pcb.png "PCB image")

## BOM

Please check [BOM.txt](BOM.txt).

## Note for assembly

 * U2: The Square pad is for pin 1.
 * It is recommended to use heatsink for U2.
 * The triple pads with rectangle near the center of the board is for U3 (right side of F1). The leftmost pad is for Vout.
   - If you use 7805 type voltage regulator, the leftmost pad is for pin 1.
 * The P3 is jumpmer pin. You can enable 5V output by shorting these pins.
 * The holes on each side can be used to mount the board. The hole spacing matches this PCB terminal [PCB-54L](https://akizukidenshi.com/catalog/g/gC-12218/) and [PCB-54R](https://akizukidenshi.com/catalog/g/gC-12219/].

## LICENSE

CC-BY 4.0 International


