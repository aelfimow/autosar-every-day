# Day 40

* From AUTOSAR\_EXP\_BSWDistributionGuide.pdf

MCAL Distribution: Constraints (p. 28)
* Access Serialization on a single core
* Access Serialization across cores
* better option: a classical master-satellite implementation basing on a proprietary (lean) `IOC`

MCAL Distribution: Definition of MCAL Users (p. 28)
* Application `SWC` (above the `RTE`) via `IoHwAbstr`
* `CDD` or `BSW` Module (below the `RTE`)

MCAL Distribution: Considering Multiple Partitions (p. 28)
* Mappable elements are not simply mapped to cores, but instead to partitions
* MCAL interfaces are not mapped to partitions
* Core scope: `GLOBAL` or `LOCAL`
* interfaces required by partitions on a single core only: `LOCAL`
* interfaces required by different partitions on a multiple cores: `GLOBAL`

MCAL Distribution: Impact on MCAL Symbol Allocation (p. 29)
