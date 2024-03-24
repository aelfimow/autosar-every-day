# Day 54

* From AUTOSAR\_EXP\_BSWDistributionGuide.pdf

BSW Distribution in Safety Systems: General overview on safety (p. 61)

BSW Distribution in Safety Systems: Safety solutions in AUTOSAR (p. 61)
* Partitioning of SWCs to support the isolation in space
* Timing and control flow supervision
* A safe communication via end-to-end protection
* `CoreTest`
* `RamTest`
* All BSW modules must be developed according the highest ASIL of the system
* QM BSW partition
* ASIL BSW partition

BSW Distribution in Safety Systems: Some modules are always ASIL (p. 64)

BSW Distribution in Safety Systems: Overall configuration (p. 64)

BSW Distribution in Safety Systems: Crossing partition boundaries (p. 66)
* `ActivateTask`
* `SetEvent`
* `CallTrustedFunction`
