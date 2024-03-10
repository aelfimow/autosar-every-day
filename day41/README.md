# Day 41

* From AUTOSAR\_EXP\_BSWDistributionGuide.pdf

MCAL Distribution: Impact on MCAL Symbol Allocation (p. 29)
* Map peripherals to cores or partitions
* Protected by further hardware, e.g. privilege levels, safety partitions
* Allocate data in the individual partitions
* Allocate the data at least with the same core scope
* Map data and related operations to the same core


Conclusion: (p. 30)
* Symbols shall be allocated with the same core scope than the APIs (internal or public) using it.
