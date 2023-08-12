[![status-badge](https://ci.codeberg.org/api/badges/12470/status.svg)](https://ci.codeberg.org/12470)

Licence | OSHWA
:-------------------------:|:-------------------------:
![](./img/oshw_facts.svg) | [![](./img/oshwa.png)](https://certification.oshwa.org/de000137.html)

# uConsole USB Hub

This extension board adds 4 additional USB ports to the [uConsole](https://www.clockworkpi.com/uconsole).

## Schematic

[![status-badge](img/schematic_low_res.png)](https://codeberg.org/argrento/uconsole-ext-usb-hub/releases)

## PCB

[![pcb-top](img/pcb_top.png)](https://codeberg.org/argrento/uconsole-ext-usb-hub/releases)
[![pcb-bottom](img/pcb_bottom.png)](https://codeberg.org/argrento/uconsole-ext-usb-hub/releases)


## Changelog
* 0.1.1
    * Schematic
        * No changes
    * PCB
        * Add OSHW certification
        * Add some info labels and QR code to this repo
* 0.1.0 -- **Production Release**
    * Schematic
        * `HUB_RESET` is now connected to `GPIO28`
        * `U3`, `U4`, `U5`, `U6` are rotated to simplify pcb
    * PCB
        * First PCB version
* 0.0.2
    * Schematic
        * Add speakers
* 0.0.1
    * Initial release