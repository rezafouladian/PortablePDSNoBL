# Portable PDS NoBL

A PDS card for the Macintosh Portable adding 8MB of RAM running at zero wait states, as well as an optional 1MB of ROM.

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
