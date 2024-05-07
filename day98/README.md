# Day 98

* From AUTOSAR\_EXP\_VFB.pdf

Communicating modes (p. 77)
* mode switch notification mechanism
* `mode-managers`
* 1:n communication only (1 mode manager and n mode users)
* mode switch communication is only supported in ECU local communication

Mode-managers: components that control modes (p. 78)
* a mode manager can have an `RPort` (to receive mode requests from a mode requestor)

Components that depend on modes (p. 79)

Specification items (p. 80)
* `EXP_Vfb_00117`
* `EXP_Vfb_00119`
