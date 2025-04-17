# Board Revision 1 Info

## DIP Switch Settings

| SW | Off | On |
| --- | --- | --- |
| 1 | 4MB RAM | 8MB RAM |
| 2 | No Diagnostic ROM | Diagnostic ROM at $F80000 |
| 3 | No ROM | ROM at $A00000 |

## Required Board Fixes
Add 10kΩ resistor from S1 to GND  
Add 10kΩ resistor from S2 to GND  
Add 10kΩ resistor from S3 to GND  
Connect U3 pin 22 to GND  
Connect U7 pin 22 to GND  
Connect U10 pin 22 to GND  

# Additional Files
Revision 1 board files and CPLD files [available here](https://github.com/rezafouladian/PortablePDSNoBL/releases/tag/rev1).
