# Day 174

* From AUTOSAR\_EXP\_CPSwClusterDesignAndIntegrationGuideline.pdf

Basic Software integration in an Application Software Cluster (p. 39)
* limited environment
* Hardware interrupts are not available
* Direct `HW` access is not supported
* interfaces of other `BSW` modules will not be available
* usage of a single core

Functional restrictions (p. 40)
* Postbuild variability for interfaces out of scope
* intra ECU signal based communciation not supported
* `SOME/IP` communciation not supported
* Access to BSW Services not supported

Flashing and Compatibility (p. 40)

Severe incompatibilities (p. 41)
* compatibility check is required 
* `Software Cluster Base Configuration Check`

Severe Connection Errors (p. 41)

Example listings (p. 42)

Referenced Meta Classes (p. 160)
