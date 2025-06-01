# IBIS to USB Converter

This project is a hardware solution for communicating with miscelaneous IBIS devices (BUSE BS210 etc.)

## Features

- Converts IBIS protocol to USB (virtual COM port)
- Mini USB
- Open hardware design (schematics and PCB in KiCad)

## Getting Started

1. Open the schematic and PCB files in KiCad.
2. Manufacture the PCB and assemble the components as specified.
3. Connect the IBIS and USB.
4. Use PuTTY to comunicate (1200 bit/s, 7 bits, even parity, 2 stop bits) or IBIS-Wagenbus Utility

## License

This project is open-source. See the LICENSE file for details.

## Credits

Developed by xtomasnemec.
Original IBIS to RS232 converter [here](https://jachyhm.cz/ois/Schemata/IBIS-COM_kompletni_schema.jpg).