# Day 75

* From AUTOSAR\_EXP\_ErrorDescription.pdf

Purpose (p. 7)
* The failure modes are assumed to be random failures related to the hardware

Purpose, Limitations (p. 7)
* Limited to the CAN communication stack
* Limited to the memory stack

Report to the Diagnostic Event Manager (`DEM`) (p. 10)

Module reporting the error: BSW (p. 10)
* `Dem_SetEventStatus`
* `Det_ReportRuntimeError`
* `Det_ReportTransientFault`

Module reporting the error: SWC (p. 10)
* `Dem_SetEventStatus`

Roles of the modules: Diagnostic Event Manager (p. 11)

Roles of the modules: `DET` (p. 11)
* runtime error: `Det_ReportRuntimeError`
* transient fault: `Det_ReportTransientFault`

Roles of the modules: Function Inhibition Manager (p. 11)

Roles of the modules: RTE (p. 12)
* provides access to the `DEM` and `FIM` operations for the SWCs

Communication related errors (p. 13)
