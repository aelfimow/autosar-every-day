# Day 32

* From AUTOSAR\_EXP\_CDDDesignAndIntegrationGuideline.pdf

CDD in multi-cores system (p. 23)
* master/satellite implementation
* reside on the same core to access standardized interfaces of the BSW
* `IOC` mechanism of the operating system

If CDD does not reside on the same core:
* use a satellite providing the standardized interface
* implement a stub part of the CDD on the other core using `IOC` mechanism
