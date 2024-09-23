# small-fry

rev. 1 prototype

## parts needed

- 1x Raspberry Pi Pico (make sure you get an [authentic one](https://www.raspberrypi.com/products/raspberry-pi-pico/) with the castellated pins)
- 69x SOD123 diodes (e.g. [1N4148W](https://www.digikey.com/en/products/detail/micro-commercial-co/1N4148W-TP/717196))
- 69 MX or Alps switches (i **strongly recommend MX** unless you are confident in fabricating your own keycaps)
- 2x 2U stabilizers
- 53x 1U keycaps
- 14x 1.75U keycaps
- 1x 2.25U keycap
- 1x 2.75U keycap

## tools needed
- **a heat gun + solder paste are highly recommended** for soldering the diodes, however they can be hand-soldered if you are patient and skilled.
- soldering iron + solder  wire for soldering the switches and MCU.

## assembly notes
- this PCB does not have holes for tray-mounting; it must be plate-mounted to a case.
- switchplate .DXF file is included; recommended material is either metal or FR4. acrylic is viable but will add flex.
- if you are making a sandwich case, the minimum required standoff height between a bottom plate and the switchplate is 8mm. any shorter will interfere with the switch fixing pins.
