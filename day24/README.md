# Day 24

* From AUTOSAR\_EXP\_ClassicPlatformARTI.pdf

Program Flow Tracing (p. 6)
* OS internal state variables can not be seen

Data Tracing (p. 6)
* instrumentation: adding manually a variable to be used in the VFB Hooks

Software Tracing (p. 7)

OS Awareness (p. 7)
* `.ORTI` file
* Software based tracing is not standardized within `ORTI`

ARTI ECU Configuration Parameter Containers (p. 9)
* `ArtiValues`: names of all ARTI relevant variables
* `ArtiOs`: all available Tasks and ISRs
* `ArtiHardware`: all references for the currently running Task and ISR OS variables for each core
* `ArtiGeneric`: additional information, which is not standardized

OS (p. 11)
