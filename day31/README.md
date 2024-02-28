# Day 31

* From AUTOSAR\_EXP\_CDDDesignAndIntegrationGuideline.pdf

Interfacing with PDU Router (p. 20)

Interfacing `<Bus>` Interfaces modules (p.20)
* Include `CDD_<MODULENAME>_Cbk.h`

Interfacing with Network Management Interface module (p. 21)
* `<Bus>Nm_CDD`

Interfacing with XCP module (p. 21)
* `<Cdd_Transmit>`
* `<Xcp_CddTxConfirmation>`
* `<Xcp_CddRxIndication>`
* `XcpOnCddEnabled` parameter

Interfacing with OS (p. 22)
* Only `GetCounterValue` and `GetElapsedCounterValue`
* Notification using `OsRestartTask`

Interfacing with StbM module (p. 23)
* `StbM_GetCurrentTime`
* `StbM_GetCurrentTimeRaw`
* `StbM_GetCurrentTimeDiff`
* `StbM_BusSetGlobalTime`
* container `CddGlobalTimeContribution` in the CDD's module definition

CDD in multi-cores system (p. 23)
