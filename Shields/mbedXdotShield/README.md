## mbedXdotShield

The mbed xDOT shield features a Multitech xDOT LORA module, with mbed compatabile drag-drop programming. This device is both a independent platform or can act as a shield to make any device send or recieve LORA data via UART.

<img src="http://i.imgur.com/FHe1Cg4.jpg" width="600" height="300" />

## Whats included here?

* Eagle Schematic and Board files
* PDF Schematic and Board copies
* CAM Job GERBERS for manufacture (including pick/place and drill)
* BOM (Bill of Materials)
* eBOM (An online BOM for easy purchasing!)

The design features:

        1. Multitech xDOT module: ST ARM® Cortex® M3 processor (STM32L151CCU6)
        2. DAPLink Interface LPC11u35: Drag Drop programming
        3. 868/915MHz LoRa chip antenna
        4. AT45DB161E-SSHD-T Serial Flash
        5. 3V JST-PH Battery connector
        6. Arduino style headers: Allowing device to operate as LoRa shield
        7. UART swap: Slide switch, allowing UART TX/RX to be swapped, if using as shield switch to 'On'

## Hardware

The hardware design files can be found in this repo as part of the mbed HDK and are referenced by their most up-to-date version v’x.x.x’.(If you wish to find an older project version, navigate to releases or checkout a previous commit).

## Software and more info

The software for tests and more info can be found in the [CI Test Shield github repository](http://www.github.com/armmbed/ci-test-shield). 

## How to get hardware

1. Buy pre-assembled board from vendor (todo)
2. Do it yourself


## Revisions
- **v 1.2.0** (23/06/17)
	-  'D2' Replaced with 'R29' 0ohm.
	-  mbed enabled logo on silkscreen
	-  Modified 'CON2' now recommended voltage is 4.5V (from 3V) for VBAT, rerouted to input of LDO 'U2'
- **v 1.1.0** (01/06/17)
	- 	'R3':1.5K->220R
	-  'R13','R14':470R->1.5K
	-  Placed resistors 'R14'-to-'R27' on front of PCB (no components on rear)
	-  Rerouted UART1TX, UART1RX (improved antenna performance)
	-  Moved USB micro further into board
- **v 1.0.0** (18/05/17)
 - Initial Commit










	
