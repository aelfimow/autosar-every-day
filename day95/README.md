# Day 95

* From AUTOSAR\_EXP\_VFB.pdf

Timing Extensions (p. 66)

Main Purpose of Timing Extensions for AUTOSAR (p. 66)
* basic entity: event
* `TimingDescriptionEvent`
* `TimingDescriptionEventChain`
* `TimingConstraint`

Timing in different phases of the AUTOSAR methodology (p. 67)
* Five different timing views
* `VfbTiming`
* `SwcTiming`
* `SystemTiming`
* `BswModuleTiming`
* `EcuTiming`

Interaction with hardware (p. 68)

Signal conversions between physical signals and software signals (p. 69)

Microcontroller Abstraction Layer (MCAL) (p. 69)
* implements notification mechanisms

ECU Abstraction (p. 70)
* example `ECU_Set_I` for the ECU abstraction

Sensor-Actuator Software Component (p. 70)
* atomic software component

Complex Driver Component (p. 70)
* loosely coupled container
* injection control
* electric valve control
* incremental position detection
* implement drivers for hardware which is not supported by AUTOSAR
* already existing applications can be defined as Complex Drivers

AUTOSAR Services (p. 72)
