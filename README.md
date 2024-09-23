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

- diode direction is COL to ROW! this means the lines should face down (if you're using the diodes linked above).
- this PCB does not have holes for tray-mounting; it must be plate-mounted to a case.
- switchplate .DXF file is included; it should be ~1.5mm thick. recommended material is either metal or FR4. acrylic is technically viable but will add flex.

### sandwich case notes

some .DXF files are included for a rudimentary sandwich case. additional hardware needed:
- 10x M3x8mm male-to-female standoffs (M3x10 will also work, just makes the height taller)
- 10x M3x4mm screws
- 10x M3x6x5mm heat-threaded inserts

required thickness of each plate:
- top plate: 1.5-3mm
- mid plate: 3mm
- buffer plate: 3mm
- bottom plate: 1.5-3mm

stacking order of plates is, from top to bottom:
- top plate
- mid plate
- buffer plate
- switch plate
- bottom plate
