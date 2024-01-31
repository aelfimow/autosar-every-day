# Day 3

* From AUTOSAR\_EXP\_LayeredSoftwareArchitecture.pdf

Microcontroller Abstraction Layer:
* Implementation depends on Microcontroller, but upper layer interface is standardized

ECU Abstraction Layer:
* Implementation depends on ECU hardware

Complex Drivers:
* Implementation "no limits" (see p.27)

Services Layer:
* Basic services for applications, RTE (Runtime Environment) and BSW (basic software modules)
* Note: Implementation mostly independent from Microcontroller and/or ECU hardware

RTE (Runtime Environment):
* Upper interface is ECU independent, but its implementation is ECU and application specific
* RTE is generated individually
