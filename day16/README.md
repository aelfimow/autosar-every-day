# Day 16

* From AUTOSAR\_EXP\_ApplicationLevelErrorHandling.pdf

Error handling strategy in the Protection Hook (p. 59)
* Partition ID: `GetApplicationID()`
* Error type
* Partition restart counter
* OS-Application State

Error handling strategy (p. 60)
* Do nothing, `PRO_IGNORE`
* Restart the partition, `PRO_TERMINATEAPPL_RESTART`
* Terminate the partition, `PRO_TERMINATEAPPL_RESTART`
* Shutdown OS/ECU, `PRO_SHUTDOWN`

Clean-up activities in BSW: (p. 63)
* `CallTrustedFunction()`

Integrator responsibility (p. 67)
* there is one global Protection Hook for the entire ECU
