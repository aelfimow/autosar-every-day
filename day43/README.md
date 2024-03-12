# Day 43

* From AUTOSAR\_EXP\_BSWDistributionGuide.pdf

Definition of MCAL Multi-Core Types: MCAL Multi-Core Module Type I
* Executable on one core only: Local service API
* Executable on one core only: One local kernel
* One HW element mappable to one core only
* Example: `FLS`, `MEMIF` and `FEE`

Definition of MCAL Multi-Core Types: MCAL Multi-Core Module Type II
* Executable on any core: Global (distributed /shared) service API
* Executable on any core: Global (distributed /shared) kernel
* One HW element mappable to one core only
* Example: `CAN`, `ETH` and `FR`

Definition of MCAL Multi-Core Types: MCAL Multi-Core Module Type III
* Executable on any core: Global (distributed /shared) service API
* Executable on any core: Global (distributed /shared) kernel
* One HW element mappable to several cores
* Example: `DIO`

Definition of MCAL Multi-Core Types: MCAL Multi-Core Module Type IV
* Executable on any core: Global (distributed /shared) service API
* Executable on one core only: One local kernel
* One HW element mappable to one core only
* Example: `ADC`, `PWM`, `ICU` and `OCU`

Definition of MCAL Multi-Core Types: MCAL Multi-Core Module Type V
* Executable on any core: Global (distributed /shared) service API
* Executable on one core only: One local kernel
* One HW element mappable to several cores
