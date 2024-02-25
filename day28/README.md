# Day 28

* From AUTOSAR\_EXP\_CDDDesignAndIntegrationGuideline.pdf

* implement complex sensor evaluation
* implement complex actuator control
* direct access to the microcontroller

CDD Implementation (p. 11)
* application dependent
* microcontroler dependent
* ECU dependent

Documentations: User's Manual (p. 12)


Module ID (p. 12)

Code files (p. 13)
* At least: `CDD_<MODULENAME>.c`
* Interrupt functions: `CDD_<MODULENAME>_Irq.c`
* Callout functions: `CDD_<MODULENAME>_Callout.c`
* Link time configuration: `CDD_<MODULENAME>_Lcfg.c`
* Post Build time configuration: `CDD_<MODULENAME>_PBcfg.c`

Header files (p. 13)
* `CDD_<MODULENAME>.h`
* callback functions: `CDD_<MODULENAME>_Cbk.h`
* Configuration: `CDD_<MODULENAME>_Cfg.h`, `CDD_<MODULENAME>_PBcfg.h`, `CDD_<MODULENAME>_Lcfg.h`

CDD module may include:
* `Det.h`
* `Dem.h`
* `<Mip>_MemMap.h`
* `Rte_CDD_<MODULENAME>.h`
