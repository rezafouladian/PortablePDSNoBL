# Portable PDS NoBL

A PDS card for the Macintosh Portable adding 8MB of RAM running at zero wait states, as well as an optional 1MB of ROM.

It uses Cypress NoBL™ (short for No Bus Latency) SRAM.

Note: To get the full 9MB total (1MB internal + 8MB expansion) on the model M5126 backlit Macintosh Portable, a mapping modification is needed on the logic board otherwise only 8MB total will be usable.

Current Revision: Rev 2  
For previous revisions, open the previous_revisions folder or [click here](previous_revisions/).

For the generated Gerber board files and CPLD files, see [Releases](https://github.com/rezafouladian/PortablePDSNoBL/releases)

## DIP Switch Settings

| SW | Off | On |
| --- | --- | --- |
| 1 | 4MB RAM | 8MB RAM |
| 2 | No Diagnostic ROM | Diagnostic ROM at $F80000 |
| 3 | No ROM | ROM at $A00000 |

## Using the ROM
Turning on DIP switch 3 will enable the ROM on the card. It is located from $A00000 to $AFFFFF in the Portable's memory space.

You can use this ROM to add ROM Disks or other code.

## Using the Diagnostic ROM
The diagnostic ROM space is placed at $F80000 in the Portable's memory space.

If you are using 4Mbit ROMs (1MB total) then the start of the diagnostic ROM space will be halfway through the ROM at $80000.  
If you use 2Mbit or smaller ROMs then you should be able to place the diagnostic code at the start of the ROM.


---

NoBL and No Bus Latency are trademarks of Cypress Semiconductor Corporation.
