# Knob
A multifunctional directional controller 

## Why?
This was inspired by both the BMW iDrive controller, and the Garmin G1000NXI avionics suite RANGE knob. The commonality between these two control interfaces is a multidirectional switch that has inputs for up, down, left, right, push, rotate ccw, and rotate cw. In the iDrive system, directional pushes move between radial menus, rotate moves between options in the menu, and push selects. This allows for intuitive control while keeping your attention focused on the road, rather than trying to poke touchscreen buttons. On the G1000NXI that I flew with at ERAU, the RANGE knob is used to zoom the map around your aircraft with rotation, panning the map, or clicking it to switch to cursor mode. In both of these situations, it has served an interesting role that no other input type could easily replace, and I thought it would be interesting to make it work on a computer.

## Assembly:
Just solder everything as shown in the KiCad Project, nothing special.

## Pics
![render](/images/rendernew.png)
![pcb](/images/pcbnew.png)
![sch](/images/schnew.png)

## BOM 
|Q  |Name             |Link                                                                                 |Price+ship                                   |Total |
|---|-----------------|-------------------------------------------------------------------------------------|---------------------------------------------|------|
|1  |Knob PCB         |                                                                                     |$8.22                                        |$30.96|
|1  |Alps RKJXT1F42001|https://www.digikey.com/en/products/detail/alps-alpine/RKJXT1F42001/19529127         |$22.74                                       |      |
|6  |SK6812MINI-E     |                                                                                     |on hand                                      |      |
|1  |XIAO RP2040      |https://www.digikey.com/en/products/detail/seeed-technology-co-ltd/102010428/14672129|included in the other to account for shipping|      |
