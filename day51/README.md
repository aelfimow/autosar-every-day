# Day 51

* From AUTOSAR\_EXP\_BSWDistributionGuide.pdf

`Com-Stack` Distribution: Constraints (p. 53)
* V2X stack has to be mapped to the same partition as the other Ethernet related modules
* J1939 stack shall be assigned to the same partition as the `DEM`

Functional Elements: `I-PDU` configuration in a distributed environment (p. 54)
* Special case: `LdCom` module is just a pure forwarding component
* `LdCom` has neither buffers nor tasks and thus no own execution context
