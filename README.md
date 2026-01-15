# USB Keychain

You might be wondering why a USB port would be added to a keychain. This project was inspired by the This project was inspired by [Sage Cadence Light-Up Keychain project](https://sites.google.com/view/sagecadence/home/light-up-keychain).


The keychain contains an LED that lights up when plugged into a USB port. Through this project, I learned more about different parts of KiCad. In order to create the USB connection, I designed a custom USB edge-connector footprint, since the PCB itself serves as the USB plug.

## Components Used
- LED  
- Resistor  
- USB edge connector (custom footprint)  
- Mounting hole (for keychain attachment)

---

## Schematic
![Schematic](images/schematic.png)

You can access the schematic file here:  
*(link to file)*

---

## PCB Layout
![PCB](images/pcb.png)

You can access the PCB file here:  
*(link to file)*

To make soldering easier, a thermal via was added near the LED ground pad.
