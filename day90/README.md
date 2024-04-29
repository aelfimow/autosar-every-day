# Day 90

* From AUTOSAR\_EXP\_VFB.pdf

Variant Handling: Variability (p. 46)

Variability: Software Component Variability (p. 46)
* existence of a Variation Point
* as late as Post Build

Variability: Port Variability (p. 46)
* latest binding time is Pre Compile time

Variability: Connector Variability (p. 47)
* latest binding time is Post BuildPre Compile time

Communication on the VFB: Error types (p. 48)
* infrastructure errors (e.g. message timeout)
* infrastructure errors are standardized by AUTOSAR
* application errors

Communication on the VFB: Sender-Receiver communication (p. 48)
* data-elements of type `last-is-best`
* data-elements of type `queued`
* `last-is-best`: `RECEIVE_INVALID` or `CAN_INVALIDATE`

Specification items (p. 49)
* `EXP_Vfb_00011`
* `EXP_Vfb_00012`
* `EXP_Vfb_00101`

Sender-Receiver communication: From the point of view of the sender (p. 50)
