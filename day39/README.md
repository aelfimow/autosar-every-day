# Day 39

* From AUTOSAR\_EXP\_BSWDistributionGuide.pdf

MCAL Distribution (p. 27)

Assumptions:
* multi-partition (multi-application) AUTOSAR operating system
* hardware implementation shall allow a mapping of peripherals at least to cores
* route hardware and software interrupts to one partition or at least a dedicated core

Relevant service modules:
* `Det`
* `Dem`
* `EcuM`
* `Os`
* `SchM`
* `NvM`
