# Day 42

* From AUTOSAR\_EXP\_BSWDistributionGuide.pdf

MCAL Distribution: Multi-Core Capabilities Classification Criteria (p. 30)

Criteria 1: APIs Availability
* Executable on one core only: Local service API
* Executable on any core: Global (distributed /shared) service API

Criteria 2: MCAL Kernel Execution Context
* Executable on one core only: One local kernel
* Executable on any core: Global (distributed /shared) kernel

Criteria 3: HW Elements Mapping
* One HW element mappable to one core only
* One HW element mappable to several cores
