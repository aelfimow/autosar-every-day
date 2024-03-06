# Day 38

* From AUTOSAR\_EXP\_BSWDistributionGuide.pdf

Task Mapping (p. 21)
* new subclasses of `BswEvent`
* `BswSchedulableEntity`
* `BswDistinguishedPartition`

General Configuration of Master and Satellites (p. 25)

Configuring the BswM (per Partition) (p. 25)
* container `BswMGeneral`
* `BswMConfig`

Configuring the `EcuM` (per Core) (p. 26)
* on every core there shall be one and only one partition that runs the `EcuM`
* `EcuM_init`

MCAL Distribution (p. 27)
