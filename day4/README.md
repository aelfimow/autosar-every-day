# Day 4

* From AUTOSAR\_EXP\_LayeredSoftwareArchitecture.pdf

Internal devices, e.g.:
* internal EEPROM
* internal ADC

External devices, e.g.:
* External EEPROM
* External watchdog

Basic Software Module types:
* __Internal driver__: driver for internal devices
* __External driver__: driver for external devices
* __Interface__
* __Handler__
* __Manager__

Note: Managers are located in the Services Layer

AUTOSAR libraries: e.g. floating point math, checksum calculation like CRC etc.

Note: AUTOSAR libraries call only libraries
