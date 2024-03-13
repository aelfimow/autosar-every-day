# Day 44

* From AUTOSAR\_EXP\_BSWDistributionGuide.pdf

Mapping MCAL Modules to Multi-Core Types (p. 35)
* `Eep`, `Fls`: Services are bound to one core

Seperation Stragies and Mapping of Elements (p. 37)
* Global data
* Shared special function registers
* Peripheral registers

MCAL drivers, elements which can have their own process context:
* Main function: Mapped- and executed in task context
* Service API: Called in the context of one or several tasks or ISR
* ISR: Called in interrupt context

Separation Strategies (p. 38)
