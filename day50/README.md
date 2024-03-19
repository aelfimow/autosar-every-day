# Day 50

* From AUTOSAR\_EXP\_BSWDistributionGuide.pdf

How to determine the Core Scope: Determining the Core Scope of MCAL symbols (p. 48)
* Single partition only (1:1 mapping): `LOCAL`
* Many partitions (1:n mapping): `GLOBAL`

How to determine the Core Scope: Applying `MemMap` to the according Multi-Core-Types

How to determine the Core Scope: Allocating driver internal symbols

`Com-Stack` Distribution (p. 52)

`Com-Stack` Distribution: Assumptions of Use (p. 53)
* Hardware implementation
* Routing of hardware and software interrupts
* `Crypto-Stack` in one partition

`Com-Stack` Distribution: Constraints (p. 53)
