# Day 99

* From AUTOSAR\_EXP\_VFB.pdf


Port Groups (p. 81)

Measurement and Calibration (p. 82)
* Measurement: monitoring of ECU internal signals, state variables and intermediate data
* Calibration: manipulation of particular calibration parameters

Port-based calibration (p. 82)
* parameter software components: components that contain the actual values of the calibration parameters

Pure single instantiation (p. 83)

Multiple instantiation of the involved software components (p. 83)
* parameter software component needs to be duplicated if the different software component instances are mapped onto different ECUs

Multiple instantiation of the involved calibration components (p. 84)

Private calibration (p. 85)
* `perInstanceParameter`
* `sharedParameter`
* Calibration parameters are not visible per se on the `VFB`

Measurement (p. 85)
