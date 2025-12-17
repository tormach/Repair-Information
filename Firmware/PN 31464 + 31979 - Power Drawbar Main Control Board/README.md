Note: 31464 is the unprogrammed PCB for 31979 (PCNC Drawbar Control Board). 

The pin out of the 31979 doesn’t match that of the PICkit 3.  Construct this conversion cable:

| Function | PICkit 3 Pin | 31979 Programming Header (DB8) |
| ------------- | ------------- | ------------- |
| MCLR Vpp| 1 | 4 |
| Vdd (+5V) | 2 | 3 |
| Vss (GND) | 3 | 5 |
| PGD | 4 | 2 |
| PGC | 5 | 1 |
| PGM | 6 | n/a |