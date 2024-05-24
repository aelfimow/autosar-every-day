# Day 115

* From AUTOSAR\_EXP\_ModeManagementGuide.pdf

`BswM` to `BswM` interaction on multicore ECUs (p. 66)
* `BswM` should be locally available on the same partition in order to limit inter-core communication as much as possible
* partition local `BswM`
* Startup up
* Shutdown
* Deinitialization
* Restart of a partition

Inter-partition Actions (p. 67)
* `BswM`: no mechanisms to prevent the execution of actions which affect modules residing on another partition
* The configurator of the `BswM` needs to be aware of this

Inter-partition Requests/Indications (p. 67)
* The configurator must take special considerations regarding: `BswMComMIndication` or `BswMGenericRequest`
* Memory protection
* Mode requests/indications configured with `IMMEDIATE`

Backward Compatibility (p. 68)
