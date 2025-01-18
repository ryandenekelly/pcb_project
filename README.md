# STM32 PCB Project
**Very much a work in progress**

PCB prototype project using KiCad and based on ST32F411RET7. 
The goal is to utilise the SSD1306 or ST7735 LCD displays and RFM69 radio to make a sensor sever / controller.

## Schematic
### MCU

Circuitry to power microcontroller and its nesessary parts.

![MCU section of the schematic](https://github.com/ryandenekelly/pcb_project/blob/master/images/schematic_mcu.PNG?raw=true)

### Power

USB-C/Battery power and regulator.

![Power section of the schematic](https://github.com/ryandenekelly/pcb_project/blob/master/images/schematic_power.PNG?raw=true)
### UART
USB-B UART input.
![UART section of the schematic](https://github.com/ryandenekelly/pcb_project/blob/master/images/schematic_uart.PNG?raw=true)
### Radio and Display
Headers for RFM69 radio and LCD displays
![Radio and display section of the schematic](https://github.com/ryandenekelly/pcb_project/blob/master/images/schematic_radio_disp.PNG?raw=true)
### Input
Push button and encoder input with filtering.
![Input section of the schematic](https://github.com/ryandenekelly/pcb_project/blob/master/images/schematic_input.PNG?raw=true)

## PCB

First version of PCB

![Full PCB](https://github.com/ryandenekelly/pcb_project/blob/master/images/pcb_all.PNG?raw=true)

### Top Layer

Top layer containing the signals and power.

![Just the top layer of the PCB](https://github.com/ryandenekelly/pcb_project/blob/master/images/pcb_front.PNG?raw=true)

### Bottom Layer

Bottom layer containing mostly the GND plane, with some signals from vias.

![Just the bottom layer of PCB](https://github.com/ryandenekelly/pcb_project/blob/master/images/pcb_back.PNG?raw=true)


### Future Improvement

Pending arrival and assemply of PCB.
